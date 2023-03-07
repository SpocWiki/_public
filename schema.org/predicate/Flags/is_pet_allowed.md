---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_pet_allowed
linkTitle: is_pet_allowed

keywords: [pet_allowed]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- pet-allowed
- pet_allowed
- petsAllowed
- is_pet_allowed
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/pet_allowed 
#is_/not_/pet_allowed 

Or write it as a Triple: 
[ is_pet_allowed :: Boolean, Text ] 

Indicates whether pets are allowed to enter the accommodation or lodging business. More detailed information can be put in a text value.

Predicate describes that: 
[ #has_/domain  :: Accommodation, ApartmentComplex, FloorPlan, LodgingBusiness ]
( #has_/name :: is_pet_allowed )
( #has_/range :: Boolean, Text )

