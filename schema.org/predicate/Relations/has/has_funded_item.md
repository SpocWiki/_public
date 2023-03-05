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
title: has_funded_item

linkTitle: has_funded_item
keywords: [funded, item]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- funded-item
- funded_item
- fundedItem
- has_funded_item
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_funded_item :: BioChemEntity, CreativeWork, Event, MedicalEntity, Organization, Person, Product ] or 
- [ has_funded_item :: BioChemEntity, CreativeWork, Event, MedicalEntity, Organization, Person, Product ] 

Indicates something directly or indirectly funded or sponsored through a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Grant&quot;&gt;Grant&lt;/a&gt;. See also &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ownershipFundingInfo&quot;&gt;ownershipFundingInfo&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Grant ]
( #has_/name :: is_funded_item )
( #has_/range :: BioChemEntity, CreativeWork, Event, MedicalEntity, Organization, Person, Product )

[ #is_/inverse_of  :: funding ]

