---
layout: post
categories: SAP Retail Hierarchy Configuration
tags: SAP Retail Hierarchy Configuration
---
One year ago I began to work in an arquitech rol that mix the functional and technical areas.
Until then, i was working as an ABAP developer.

After some analyzed requirements, I realize that a los of configuration was made in different levels, but generally, this configuration is defined in a static way.

Generally the configurations need to be performed at different levels of the following hierarchies:
* Product hierarchy.
* Organizational hierarchy.

Generally, the levels at organizational hierarchy are default for every company:
1. The whole company (root).
2. Sales organization.
3. Distribution Channel.
4. Store.

By the other hand Product hierarchy depends a lot in design desitions during system implementations.
As an example, we can have the following levels:
1. The whole product hierarchy (root).
2. Sector.
3. Group.
4. Subgroup.
5. Family.
6. Material.

At the begining of the post I mentioned that the configuration is defined in static way.
That meas that
