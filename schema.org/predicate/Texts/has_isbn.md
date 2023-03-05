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

title: has_text_about_isbn
linkTitle: has_text_about_isbn

keywords: [isbn]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- isbn
- isbn
- isbn
- has_text_about_isbn
---

Predicate to describe the Text of Book.

Use it like this: 
- [ #has_/text/_about_isbn :: Text ] or 
- [ has_text_about_isbn :: Text ] 

The ISBN of the book.

Predicated describes that: 
[ #has_/domain  :: Book ]
( #has_/name :: has_text_about_isbn )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

