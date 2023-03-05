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
title: has_legislation_passed_by

linkTitle: has_legislation_passed_by
keywords: [legislation, passed, by]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- legislation-passed-by
- legislation_passed_by
- legislationPassedBy
- has_legislation_passed_by
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_legislation_passed_by :: Organization, Person ] or 
- [ has_legislation_passed_by :: Organization, Person ] 

The person or organization that originally passed or made the law: typically parliament (for primary legislation) or government (for secondary legislation). This indicates the &quot;legal author&quot; of the law, as opposed to its physical author.

Relation describes that: 
[ #has_/domain  :: Legislation ]
( #has_/name :: is_legislation_passed_by )
( #has_/range :: Organization, Person )

[ #is_/sub_property_of  :: creator ]

