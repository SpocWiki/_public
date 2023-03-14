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
title: has_interacting_drug

linkTitle: has_interacting_drug
keywords: [interacting, drug]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- interacting-drug
- interacting_drug
- interactingDrug
- has_interacting_drug
---

Use it like this: 
- [ #has/_interacting_drug :: Drug ] or 
- [ has_interacting_drug :: Drug ] 

Another drug that is known to interact with this drug in a way that impacts the effect of this drug or causes a risk to the patient. Note: disease interactions are typically captured as contraindications.

Relation describes that: 
[ #has_/domain  :: Drug ]
( #has_/name :: has_interacting_drug )
( #has_/range :: Drug )

