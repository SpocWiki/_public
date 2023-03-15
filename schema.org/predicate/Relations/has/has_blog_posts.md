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
title: has_blog_posts

linkTitle: has_blog_posts
keywords: [blog, posts]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- blog-posts
- blog_posts
- blogPosts
- has_blog_posts
---

[ superseded_by :: blogPost]

Use it like this: 
- [ #has/_blog_post :: BlogPosting ] or 
- [ has_blog_post :: BlogPosting ] 

Indicates a post that is part of a [[Blog]]. Note that historically, what we term a "Blog" was once known as a "weblog", and that what we term a "BlogPosting" is now often colloquially referred to as a "blog".

Relation describes that: 
[ #has_/domain  :: Blog ]
( #has_/name :: has_blog_posts )
( #has_/range :: BlogPosting )

