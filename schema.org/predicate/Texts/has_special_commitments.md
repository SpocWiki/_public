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

title: has_text_about_special_commitments
linkTitle: has_text_about_special_commitments

keywords: [special, commitments]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- special-commitments
- special_commitments
- specialCommitments
- has_text_about_special_commitments
---

Predicate to describe the Text of JobPosting.

Use it like this: 
- [ #has_/text/_about_special_commitments :: Text ] or 
- [ has_text_about_special_commitments :: Text ] 

Any special commitments associated with this job posting. Valid entries include VeteranCommit, MilitarySpouseCommit, etc.

Predicated describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: has_text_about_special_commitments )
( #has_/range :: Text )

