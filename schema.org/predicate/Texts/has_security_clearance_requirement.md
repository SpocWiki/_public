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

title: has_text_about_security_clearance_requirement
linkTitle: has_text_about_security_clearance_requirement

keywords: [security, clearance, requirement]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- security-clearance-requirement
- security_clearance_requirement
- securityClearanceRequirement
- has_text_about_security_clearance_requirement
---

Predicate to describe the Text of JobPosting.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_security_clearance_requirement :: Text, URL ] or 
- [ has_text_about_security_clearance_requirement :: Text, URL ] 

A description of any security clearance requirements of the job.

Predicated describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: is_security_clearance_requirement )
( #has_/range :: Text, URL )

