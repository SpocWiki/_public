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

title: has_text_about_employment_type
linkTitle: has_text_about_employment_type

keywords: [employment, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- employment-type
- employment_type
- employmentType
- has_text_about_employment_type
---

Predicate to describe the Text of JobPosting.

Use it like this: 
- [ #has_/text/_about_employment_type :: Text ] or 
- [ has_text_about_employment_type :: Text ] 

Type of employment (e.g. full-time, part-time, contract, temporary, seasonal, internship).

Predicated describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: is_employment_type )
( #has_/range :: Text )

