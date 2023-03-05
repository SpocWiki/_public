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
title: has_bed

linkTitle: has_bed
keywords: [bed]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- bed
- bed
- bed
- has_bed
---

Use it like this: 
- [ #has/_bed :: BedDetails, BedType, Text ] or 
- [ has_bed :: BedDetails, BedType, Text ] 

The type of bed or beds included in the accommodation. For the single case of just one bed of a certain type, you use bed directly with a text.
      If you want to indicate the quantity of a certain kind of bed, use an instance of BedDetails. For more detailed information, use the amenityFeature property.

Relation describes that: 
[ #has_/domain  :: HotelRoom, Suite ]
( #has_/name :: is_bed )
( #has_/range :: BedDetails, BedType, Text )

