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

title: has_text_about_term_code
linkTitle: has_text_about_term_code

keywords: [term, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- term-code
- term_code
- termCode
- has_text_about_term_code
---

Predicate to describe the Text of DefinedTerm.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_term_code :: Text ] or 
- [ has_text_about_term_code :: Text ] 

A code that identifies this [[DefinedTerm]] within a [[DefinedTermSet]]

Predicated describes that: 
[ #has_/domain  :: DefinedTerm ]
( #has_/name :: has_text_about_term_code )
( #has_/range :: Text )

[ #has_/sub_properties :: [ codeValue ] ]

