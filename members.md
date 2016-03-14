---
layout: page
title: Members list
permalink: /members/
---

# UniGDC Members List

UniGDC is made up of following members.

<ul id="members">
{% for member in site.data.members %}
    <li>  {{ member.name }} <a href="mailto:{{ member.email }}" class="member-contact"><i class="fa fa-envelope-o"></i></a> (<a href="https://github.com/{{ member.contact.github }}" class="member-contact">See GitHub Profile</a>) </li>
{% endfor %}
</ul>