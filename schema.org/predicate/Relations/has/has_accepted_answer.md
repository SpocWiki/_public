---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_accepted_answer

linkTitle: has_accepted_answer
keywords: [accepted, answer]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- accepted-answer
- accepted_answer
- acceptedAnswer
- has_accepted_answer
---

Use it like this: 
- [ #has/_accepted_answer :: Answer, ItemList ] or 
- [ has_accepted_answer :: Answer, ItemList ] 

The answer(s) that has been accepted as best, typically on a Question/Answer site. Sites vary in their selection mechanisms, e.g. drawing on community opinion and/or the view of the Question author.

Relation describes that: 
[ #has_/domain  :: Question ]
( #has_/name :: is_accepted_answer )
( #has_/range :: Answer, ItemList )

[ #is_/sub_property_of  :: [[has_suggested_answer]] ]

