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

title: has_text_about_article_section
linkTitle: has_text_about_article_section

keywords: [article, section]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- article-section
- article_section
- articleSection
- has_text_about_article_section
---

Predicate to describe the Text of Article.

Use it like this: 
- [ #has_/text/_about_article_section :: Text ] or 
- [ has_text_about_article_section :: Text ] 

Articles may belong to one or more "sections" in a magazine or newspaper, such as Sports, Lifestyle, etc.

Predicated describes that: 
[ #has_/domain  :: Article ]
( #has_/name :: is_article_section )
( #has_/range :: Text )

