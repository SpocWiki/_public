---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_schedule_timezone
linkTitle: has_text_about_schedule_timezone

keywords: [schedule, timezone]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- schedule-timezone
- schedule_timezone
- scheduleTimezone
- has_text_about_schedule_timezone
---

Predicate to describe the Text of Schedule.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_schedule_timezone :: Text ] or 
- [ has_text_about_schedule_timezone :: Text ] 

Indicates the timezone for which the time(s) indicated in the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Schedule&quot;&gt;Schedule&lt;/a&gt; are given. The value provided should be among those listed in the IANA Time Zone Database.

Predicated describes that: 
[ #has_/domain  :: Schedule ]
( #has_/name :: has_text_about_schedule_timezone )
( #has_/range :: Text )

