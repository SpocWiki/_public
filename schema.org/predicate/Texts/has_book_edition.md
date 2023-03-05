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

title: has_text_about_book_edition
linkTitle: has_text_about_book_edition

keywords: [book, edition]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- book-edition
- book_edition
- bookEdition
- has_text_about_book_edition
---

Predicate to describe the Text of Book.

Use it like this: 
- [ #has_/text/_about_book_edition :: Text ] or 
- [ has_text_about_book_edition :: Text ] 

The edition of the book.

Predicated describes that: 
[ #has_/domain  :: Book ]
( #has_/name :: is_book_edition )
( #has_/range :: Text )

