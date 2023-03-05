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

title: has_text_about_article_body
linkTitle: has_text_about_article_body

keywords: [article, body]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- article-body
- article_body
- articleBody
- has_text_about_article_body
---

Predicate to describe the Text of Article.

Use it like this: 
- [ #has_/text/_about_article_body :: Text ] or 
- [ has_text_about_article_body :: Text ] 

The actual body of the article.

Predicated describes that: 
[ #has_/domain  :: Article ]
( #has_/name :: has_text_about_article_body )
( #has_/range :: Text )

