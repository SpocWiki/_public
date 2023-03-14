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
title: is_alumni_of

linkTitle: is_alumni_of
keywords: [alumni, of]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- alumni-of
- alumni_of
- alumniOf
- is_alumni_of
---

Use it like this: 
- [ #is/_alumni_of :: EducationalOrganization, Organization ] or 
- [ is_alumni_of :: EducationalOrganization, Organization ] 

An organization that the person is an alumni of.

Relation describes that: 
[ #has_/domain  :: Person ]
( #has_/name :: is_alumni_of )
( #has_/range :: EducationalOrganization, Organization )

[ #is_/inverse_of  :: [[has_alumni]] ]

