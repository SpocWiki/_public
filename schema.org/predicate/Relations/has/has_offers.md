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
title: has_offers

linkTitle: has_offers
keywords: [offers]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- offers
- offers
- offers
- has_offers
---

Use it like this: 
- [ #has/_offers :: Demand, Offer ] or 
- [ has_offers :: Demand, Offer ] 

An offer to provide this item&amp;#x2014;for example, an offer to sell a product, rent the DVD of a movie, perform a service, or give away tickets to an event. Use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/businessFunction&quot;&gt;businessFunction&lt;/a&gt; to indicate the kind of transaction offered, i.e. sell, lease, etc. This property can also be used to describe a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Demand&quot;&gt;Demand&lt;/a&gt;. While this property is listed as expected on a number of common types, it can be used in others. In that case, using a second type, such as Product or a subtype of Product, can clarify the nature of the offer.

Relation describes that: 
[ #has_/domain  :: AggregateOffer, CreativeWork, EducationalOccupationalProgram, Event, MenuItem, Product, Service, Trip ]
( #has_/name :: is_offers )
( #has_/range :: Demand, Offer )

[ #is_/inverse_of  :: itemOffered ]

