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

title: has_text_about_pagination
linkTitle: has_text_about_pagination

keywords: [pagination]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- pagination
- pagination
- pagination
- has_text_about_pagination
---

Predicate to describe the Text of Article, Chapter, PublicationIssue, PublicationVolume.

Use it like this: 
- [ #has_/text/_about_pagination :: Text ] or 
- [ has_text_about_pagination :: Text ] 

Any description of pages that is not separated into pageStart and pageEnd; for example, &quot;1-6, 9, 55&quot; or &quot;10-12, 46-49&quot;.

Predicated describes that: 
[ #has_/domain  :: Article, Chapter, PublicationIssue, PublicationVolume ]
( #has_/name :: is_pagination )
( #has_/range :: Text )

