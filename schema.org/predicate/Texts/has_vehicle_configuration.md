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

title: has_text_about_vehicle_configuration
linkTitle: has_text_about_vehicle_configuration

keywords: [vehicle, configuration]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- vehicle-configuration
- vehicle_configuration
- vehicleConfiguration
- has_text_about_vehicle_configuration
---

Predicate to describe the Text of Vehicle.

Use it like this: 
- [ #has_/text/_about_vehicle_configuration :: Text ] or 
- [ has_text_about_vehicle_configuration :: Text ] 

A short text indicating the configuration of the vehicle, e.g. "5dr hatchback ST 2.5 MT 225 hp" or "limited edition".

Predicated describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: is_vehicle_configuration )
( #has_/range :: Text )

