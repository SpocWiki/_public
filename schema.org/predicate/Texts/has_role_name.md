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

title: has_text_about_role_name
linkTitle: has_text_about_role_name

keywords: [role, name]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: namedPosition

tags:
- schema.org/Predicate/Text

aliases:
- role-name
- role_name
- roleName
- has_text_about_role_name
---

Predicate to describe the Text of Role.

Use it like this: 
- [ #has_/text/_about_role_name :: Text, URL ] or 
- [ has_text_about_role_name :: Text, URL ] 

A role played, performed or filled by a person or organization. For example, the team of creators for a comic book might fill the roles named "inker", "penciller", and "letterer"; or an athlete in a SportsTeam might play in the position named "Quarterback".

Predicated describes that: 
[ #has_/domain  :: Role ]
( #has_/name :: is_role_name )
( #has_/range :: Text, URL )

