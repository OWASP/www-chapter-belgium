---
title: archive
displaytext: Past Meetings
layout: null
tab: true
order: 3
tags: belgium

---
<p>
{% assign nowTS = 'now' | date: '%s' %}
{% assign sortedMeetings = site.data.meetings %}
{% for folder in sortedMeetings reversed %}
    <h1>{{folder[0]}} Chapter Meetings</h1>
    <ul>
    {% for file in folder[1] reversed %}
      {% for meeting in file[1] %}
        {% assign dayTS = meeting.day | date: '%s' %}
        {% if nowTS >= dayTS %}

          {% assign day = meeting.day | date: '%-d' %}
          {% assign meetingDayTemp = meeting.day | date: '%A %B %-d' %}
          {% case day %}
              {% when '1' or '21' or '31' %}{% assign suffix = "st" %}
              {% when '2' or '22' %}{% assign suffix = "nd" %}
              {% when '3' or '23' %}{% assign suffix = "rd" %}
          {% else %}{% assign suffix = "th" %}
          {% endcase %}
          {% assign year = meeting.day | date: ", %Y" %}
          {% assign meetingDay = meetingDayTemp | append: suffix | append: year %}
          <h2>{{meetingDay}}</h2>
          <p>{{meeting.description}}</p>
          {% if meeting.event[0].name %}
            <h3 id="agenda">Agenda</h3>
            <ul>
            {% for event in meeting.event %}
              <li>{{event.time}} - {{event.name}}
              {% if event.title %}
                : {{event.title}}<br>
                {% if event.feed %}
                  <a href="{{event.feed}}">[Youtube feed]</a>
                {% endif %}
                {% if event.url %}
                  <a href="{{event.url}}">[
                    {% if event.urltag %}
                      {{event.urltag}}
                    {% endif %}
                   Slides]</a>
                {% endif %}
              {% endif %}
              </li>
            {% endfor %}
            </ul>
            {% if meeting.city %}
              <h3 id="location">Location</h3>
              <p>The event took place in {{meeting.city}}.</p>
            {% endif %}
          {% endif %}
        {% endif %}
      {% endfor %}  
    {% endfor %}
    </ul>
{% endfor %}
