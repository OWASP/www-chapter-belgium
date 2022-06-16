---

layout: col-sidebar
title: OWASP Belgium
tags: belgium
level: 3
region: Europe
meetup-group: belgium-owasp-meetup-group

---
Welcome to the Belgium chapter homepage. The chapter leaders are
[Sebastien Deleersnyder](mailto:seba@owasp.org),
[Lieven Desmet](mailto:lieven.desmet@owasp.org),
[Bart De Win](mailto:bart.dewin@owasp.org), and
[David Mathy](mailto:david.mathy@owasp.org).

With the Belgium chapter, we aim to organize 4 local chapter meetings per year and co-organize the yearly BeNeLux Day.\
Any suggestions for speakers or venue? Feel free to reach out to us!

# Upcoming events

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
              : <a href="{{site.url}}/#div-meetings">{{event.title}}</a>
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
        {% endif %}
      {% endfor %}  
    {% endfor %}
    </ul>
{% endfor %}
</p>

Our meetings are open to the public, and you do not need to be a member to attend. Please do consider [joining OWASP](https://owasp.org/membership/) if you find our community, projects, and meetings valuable, or sponsoring this chapter.

**More events and info**: [on the 'Chapter Meetings' tab](https://owasp.org/www-chapter-belgium/#div-meetings).

## Chapter sponsors
{% include sponsors.md %}
