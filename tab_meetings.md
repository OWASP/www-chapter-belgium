---
title: meetings
displaytext: Chapter Meetings
layout: null
tab: true
order: 2
tags: belgium
---
<p>
{% assign nowTS = 'now' | date: '%s' %}
{% assign sortedMeetings = site.data.meetings %}
{% for folder in sortedMeetings reversed %}
    <ul>
    {% for file in folder[1] reversed %}
      {% for meeting in file[1] %}
        {% assign dayTS = meeting.day | date: '%s' %}
        {% if nowTS <= dayTS %}

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
          <h1>{{meetingDay}}</h1>

          <p>{{meeting.description}}</p>
          <h2 id="agenda">Agenda</h2>
          <ul>
          {% for event in meeting.event %}
            <li>{{event.time}} - {{event.name}}
            {% if event.title %}
              : {{event.title}}
            {% endif %}
            </li>
          {% endfor %}
          </ul>
          {% if meeting.location %}
            <h2 id="location">Location</h2>
            <p>The event will take place in
            {% if meeting.locationMaps %}
              <a href="{{meeting.locationMaps}}">
            {% endif %}
            {{meeting.location}}
            {% if meeting.locationMaps %}
            </a>
            {% endif %}
            .</p>
          {% endif %}
          {% if meeting.registrationUrl %}
            <h2 id="registration">Registration</h2>
            <p><a href="{{meeting.registrationUrl}}">Register NOW</a> on meetup.com to attend this event</p>
          {% endif %}
          <h2 id="topics">Topics</h2>
          <ul>
          {% for event in meeting.event %}
            {% if event.title %}
              <li><h3 id="event.title">{{event.title}} (by {{event.name}})</h3></li>
              <h3 id="event.title">Abstract</h3>
                {% if event.abstract %}
                  <p>{{event.abstract}}</p>
                {% else %}
                  <p>Abstract coming soon...</p>
                {% endif %}
              <h3 id="event.name">Bio</h3>
                {% if event.bio %}
                  <p>{{event.bio}}</p>
                {% else %}
                  <p>{{event.name}}'s bio coming soon...</p>
                {% endif %}
            {% endif %}
          {% endfor %}
          </ul>

        {% endif %}
      {% endfor %}  
    {% endfor %}
    </ul>
{% endfor %}
