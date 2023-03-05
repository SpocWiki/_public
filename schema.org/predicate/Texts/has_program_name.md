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

title: has_text_about_program_name
linkTitle: has_text_about_program_name

keywords: [program, name]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- program-name
- program_name
- programName
- has_text_about_program_name
---

Predicate to describe the Text of ProgramMembership.

Use it like this: 
- [ #has_/text/_about_program_name :: Text ] or 
- [ has_text_about_program_name :: Text ] 

The program providing the membership.

Predicated describes that: 
[ #has_/domain  :: ProgramMembership ]
( #has_/name :: is_program_name )
( #has_/range :: Text )

