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

title: has_text_about_global_location_number
linkTitle: has_text_about_global_location_number

keywords: [global, location, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- global-location-number
- global_location_number
- globalLocationNumber
- has_text_about_global_location_number
---

Predicate to describe the Text of Organization, Person, Place.

Use it like this: 
- [ #has_/text/_about_global_location_number :: Text ] or 
- [ has_text_about_global_location_number :: Text ] 

The &lt;a href&#x3D;&quot;http://www.gs1.org/gln&quot;&gt;Global Location Number&lt;/a&gt; (GLN, sometimes also referred to as International Location Number or ILN) of the respective organization, person, or place. The GLN is a 13-digit number used to identify parties and physical locations.

Predicated describes that: 
[ #has_/domain  :: Organization, Person, Place ]
( #has_/name :: has_text_about_global_location_number )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

