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

title: has_text_about_serial_number
linkTitle: has_text_about_serial_number

keywords: [serial, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- serial-number
- serial_number
- serialNumber
- has_text_about_serial_number
---

Predicate to describe the Text of Demand, IndividualProduct, Offer.

Use it like this: 
- [ #has_/text/_about_serial_number :: Text ] or 
- [ has_text_about_serial_number :: Text ] 

The serial number or any alphanumeric identifier of a particular product. When attached to an offer, it is a shortcut for the serial number of the product included in the offer.

Predicated describes that: 
[ #has_/domain  :: Demand, IndividualProduct, Offer ]
( #has_/name :: is_serial_number )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

[ #has_/sub_properties :: [ vehicleIdentificationNumber ] ]

