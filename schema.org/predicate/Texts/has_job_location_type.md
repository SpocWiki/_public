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

title: has_text_about_job_location_type
linkTitle: has_text_about_job_location_type

keywords: [job, location, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- job-location-type
- job_location_type
- jobLocationType
- has_text_about_job_location_type
---

Predicate to describe the Text of JobPosting.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_job_location_type :: Text ] or 
- [ has_text_about_job_location_type :: Text ] 

A description of the job location (e.g. TELECOMMUTE for telecommute jobs).

Predicated describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: has_text_about_job_location_type )
( #has_/range :: Text )

