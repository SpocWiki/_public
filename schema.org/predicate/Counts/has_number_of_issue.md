---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_issue_number
linkTitle: has_number_of_issue_number

keywords: [issue_number]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- issue-number
- issue_number
- issueNumber
- has_number_of_issue
---

Predicate to describe the Number of PublicationIssue.

Use it like this: 
- [ #has_/number/_of_issue :: Integer, Text ] or 
- [ has_number_of_issue :: Integer, Text ] 

Identifies the issue of publication; for example, "iii" or "2".

Predicate describes that: 
[ #has_/domain  :: PublicationIssue ]
( #has_/name :: has_number_of_issue )
( #has_/range :: Integer, Text )

[ #is_/sub_property_of  :: position ]

