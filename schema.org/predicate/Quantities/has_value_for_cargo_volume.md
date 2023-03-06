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

title: has_cargo-volume
linkTitle: has_cargo-volume

keywords: [cargo-volume]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- cargo_volume
- cargo-volume
- cargoVolume
- has_value_for_cargo_volume
---

Predicate to describe the Quantity of Vehicle.

Use it like this: 
- [ #has_/value/_for_cargo_volume :: QuantitativeValue ] or 
- [ has_value_for_cargo_volume :: QuantitativeValue ] 

The available volume for cargo or luggage. For automobiles, this is usually the trunk volume.&lt;br/&gt;&lt;br/&gt;

Typical unit code(s): LTR for liters, FTQ for cubic foot/feet&lt;br/&gt;&lt;br/&gt;

Note: You can use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/minValue&quot;&gt;minValue&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/maxValue&quot;&gt;maxValue&lt;/a&gt; to indicate ranges.

Predicate describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_value_for_cargo_volume )
( #has_/range :: QuantitativeValue )

