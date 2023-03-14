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
title: has_funding

linkTitle: has_funding
keywords: [funding]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- funding
- funding
- funding
- has_funding
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_funding :: Grant ] or 
- [ has_funding :: Grant ] 

A &lt;a class="localLink" href="/Grant"&gt;Grant&lt;/a&gt; that directly or indirectly provide funding or sponsorship for this item. See also &lt;a class="localLink" href="/ownershipFundingInfo"&gt;ownershipFundingInfo&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: BioChemEntity, CreativeWork, Event, MedicalEntity, Organization, Person, Product ]
( #has_/name :: has_funding )
( #has_/range :: Grant )

[ #is_/inverse_of  :: [[is_funding_item]] ]

