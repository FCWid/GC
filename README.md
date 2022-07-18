GLPI entityCategory Plugin
=========================

By Probesys: https://probesys.com

Language: french

Works with: GLPI 9.5.X ( tested with 9.5.1 )

This plugin customizes the list of accessible ticket categories for ticket requesters.

Features
========

* configure list of allowed/disallowed categories for every entity. Go to Administration -> Entities -> select a entity -> scroll down. Example: entity XYZ can have category ABC, but entity UVW won't.
* change the list of available categories on the ticket creation form. Example: If the requester of a ticket is in entity XYZ, the categories will include ABC. If the requester is in entity UVW, category ABC won't be available.
* if a entity's allowed categories list is empty, requesters in this entity will have access to nearly all categories (depending on entities and if the categories are recursive)

Known issues
============

* none yet

Possible evolutions
===================

* Add category configuration through massive actions on entitys
* The same feature could be applied for entities. If you have a lot of categories it would be easier to make them accessible to entities instead of recreating them one by one.
