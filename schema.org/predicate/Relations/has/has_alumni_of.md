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
title: has_alumni_of

linkTitle: has_alumni_of
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- alumni-of
- alumni_of
- alumniOf
- has_alumni_of
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_alumni_of :: EducationalOrganization, Organization] or 
- [ has_alumni_of :: EducationalOrganization, Organization] 

An organization that the person is an alumni of.

Relation describes that: 
[ #has_/domain  :: Person]
( #has_/name :: is_alumni_of)
( #has_/range :: EducationalOrganization, Organization)

[ #is_/inverse_of  :: alumni]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
