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
title: has_service_operator

linkTitle: has_service_operator
keywords: [service, operator]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- service-operator
- service_operator
- serviceOperator
- has_service_operator
---

Use it like this: 
- [ #has/_service_operator :: Organization ] or 
- [ has_service_operator :: Organization ] 

The operating organization, if different from the provider.  This enables the representation of services that are provided by an organization, but operated by another organization like a subcontractor.

Relation describes that: 
[ #has_/domain  :: GovernmentService ]
( #has_/name :: is_service_operator )
( #has_/range :: Organization )

