---
layout: default
keywords:
comments: false

title: Office Hours
description: Times and locations may occasionally change each week; please check this page often.
buttons: [project_appt_calendly, queuestatus]
micro_nav: false
---

## Office Hours Table <a name="table"></a>

| TA | Project Office Hour Signup | Zoom URL |
|----|:--------------------------:|----------|
{% assign people = site.course.ta | concat: site.course.staff -%}
{% for ta in people -%}
{% unless ta.zoom_id == null -%}
| {{ ta.name }} | [Click to book]({{ ta.calendly }}) | [{{ ta.zoom_id }}](https://stanford.zoom.us/j/{{ ta.zoom_id }}) |
{% endunless -%}
{% endfor %}

QueueStatus link for Homework OH: [{{ site.course.queuestatus.url }}]({{ site.course.queuestatus.url }})

## Google Calendar

**All Office Hours are held remotely over Zoom. Use the Zoom link above for the respective TA.**

<div>
<iframe src="https://calendar.google.com/calendar/embed?src=o04tbuc0j3bo0ppafpju8g0h04%40group.calendar.google.com&ctz=America%2FLos_Angeles" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
</div>
