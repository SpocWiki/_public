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
title: has_result_comment

linkTitle: has_result_comment
keywords: [result, comment]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- result-comment
- result_comment
- resultComment
- has_result_comment
---

Use it like this: 
- [ #has/_result_comment :: Comment ] or 
- [ has_result_comment :: Comment ] 

A sub property of result. The Comment created or sent as a result of this action.

Relation describes that: 
[ #has_/domain  :: CommentAction, ReplyAction ]
( #has_/name :: is_result_comment )
( #has_/range :: Comment )

[ #is_/sub_property_of  :: result ]

