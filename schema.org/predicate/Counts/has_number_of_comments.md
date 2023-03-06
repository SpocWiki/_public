---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_comment_count
linkTitle: has_number_of_comment_count

keywords: [comment_count]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- comment-count
- comment_count
- commentCount
- has_number_of_comments
---

Predicate to describe the Number of CreativeWork.

Use it like this: 
- [ #has_/number/_of_comments :: Integer ] or 
- [ has_number_of_comments :: Integer ] 

The number of comments this CreativeWork (e.g. Article, Question or Answer) has received. This is most applicable to works published in Web sites with commenting system; additional comments may exist elsewhere.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_number_of_comments )
( #has_/range :: Integer )

