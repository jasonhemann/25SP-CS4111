---
title: People
layout: single
collection: people
---

{% assign person = site.data.authors[site.author] %}

## Instructor

You can find out more about me via my website, at the root of this same
domain.

| Name | Contact Address | Office Hours | Office Hours Location |
|------|-----------------|--------------|-----------------------|
| {{ person.name }} | [{{ person.emailaddr }}](mailto:{{ person.emailaddr }}) | {{ person.office_hours }} | {{ person.office_hours_location }} |

During office hours, I am also on Teams. If you cannot be in the office,
feel free to call.

{% if site.data.personnel and site.data.personnel.size > 0 %}
## Course Staff

| Name | Role | Contact Address | Office Hours | Office Hours Location |
|------|------|-----------------|--------------|-----------------------|
{% for staff in site.data.personnel %}| {{ staff.name }} | {{ staff.role }} | [{{ staff.email }}](mailto:{{ staff.email }}) | {{ staff.office_hours }} | {{ staff.office_hours_location }} |
{% endfor %}
{% endif %}

![Logical Distortion]({{ site.baseurl }}/assets/images/aura-of-logical-distortion.gif "Sometimes it helps just having someone else around")
