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

## Clinical Fellows & Residents

{% include list.html data="members" component="portrait" filter="role == 'clinical fellow' and !alumni" %}

{% include section.html %}

## Postdoctoral Fellows

{% include list.html data="members" component="portrait" filter="role == 'postdoc' and !alumni" %}

{% include section.html %}

## Research Staff

{% include list.html data="members" component="portrait" filter="role == 'research support' and !alumni" %}

{% include section.html %}

## Graduate Students

{% include list.html data="members" component="portrait" filter="role == 'grad' and !alumni" %}

{% include section.html %}

## Undergraduate Students

{% include list.html data="members" component="portrait" filter="role == 'undergrad' and !alumni" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="alumni" style="small" %}