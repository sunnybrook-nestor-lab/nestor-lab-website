---
title: Team
nav:
  order: 5
  tooltip: Meet our Team
---

# Team

{% include section.html %}

## Principal Investigator

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}

{% include section.html %}

## Lab Members

{% include list.html data="members" component="portrait" filter="role != 'pi' and !alumni" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="alumni" style="small" %}
