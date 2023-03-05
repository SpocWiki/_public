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
title: has_item_offered

linkTitle: has_item_offered
keywords: [item, offered]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- item-offered
- item_offered
- itemOffered
- has_item_offered
---

Use it like this: 
- [ #has/_item_offered :: AggregateOffer, CreativeWork, Event, MenuItem, Product, Service, Trip ] or 
- [ has_item_offered :: AggregateOffer, CreativeWork, Event, MenuItem, Product, Service, Trip ] 

An item being offered (or demanded). The transactional nature of the offer or demand is documented using &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/businessFunction&quot;&gt;businessFunction&lt;/a&gt;, e.g. sell, lease etc. While several common expected types are listed explicitly in this definition, others can be used. Using a second type, such as Product or a subtype of Product, can clarify the nature of the offer.

Relation describes that: 
[ #has_/domain  :: Demand, Offer ]
( #has_/name :: is_item_offered )
( #has_/range :: AggregateOffer, CreativeWork, Event, MenuItem, Product, Service, Trip )

[ #is_/inverse_of  :: offers ]

