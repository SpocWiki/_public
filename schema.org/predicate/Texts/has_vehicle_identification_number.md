---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_vehicle_identification_number
linkTitle: has_text_about_vehicle_identification_number

keywords: [vehicle, identification, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- vehicle-identification-number
- vehicle_identification_number
- vehicleIdentificationNumber
- has_text_about_vehicle_identification_number
---

Predicate to describe the Text of Vehicle.

Use it like this: 
- [ #has_/text/_about_vehicle_identification_number :: Text ] or 
- [ has_text_about_vehicle_identification_number :: Text ] 

The Vehicle Identification Number (VIN) is a unique serial number used by the automotive industry to identify individual motor vehicles.

Predicated describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_text_about_vehicle_identification_number )
( #has_/range :: Text )

[ #is_/sub_property_of  :: serialNumber ]

