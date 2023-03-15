---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_floor-size
linkTitle: has_floor-size

keywords: [floor-size]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- floor_size
- floor-size
- floorSize
- has_value_for_floor_size_m2
---

Predicate to describe the Quantity of Accommodation, FloorPlan.

Use it like this: 
- [ #has_/value/_for_floor_size_m2 :: QuantitativeValue ] or 
- [ has_value_for_floor_size_m2 :: QuantitativeValue ] 

The size of the accommodation, e.g. in square meter or squarefoot.
Typical unit code(s): MTK for square meter, FTK for square foot, or YDK for square yard

Predicate describes that: 
[ #has_/domain  :: Accommodation, FloorPlan ]
( #has_/name :: has_value_for_floor_size_m2 )
( #has_/range :: QuantitativeValue )

