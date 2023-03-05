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

title: has_text_about_work_hours
linkTitle: has_text_about_work_hours

keywords: [work, hours]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- work-hours
- work_hours
- workHours
- has_text_about_work_hours
---

Predicate to describe the Text of JobPosting.

Use it like this: 
- [ #has_/text/_about_work_hours :: Text ] or 
- [ has_text_about_work_hours :: Text ] 

The typical working hours for this job (e.g. 1st shift, night shift, 8am-5pm).

Predicated describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: has_text_about_work_hours )
( #has_/range :: Text )

