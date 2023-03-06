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

title: has_tongue-weight
linkTitle: has_tongue-weight

keywords: [tongue-weight]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- tongue_weight
- tongue-weight
- tongueWeight
- has_value_for_tongue_weight_kg
---

Predicate to describe the Quantity of Vehicle.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_tongue_weight_kg :: QuantitativeValue ] or 
- [ has_value_for_tongue_weight_kg :: QuantitativeValue ] 

The permitted vertical load (TWR) of a trailer attached to the vehicle. Also referred to as Tongue Load Rating (TLR) or Vertical Load Rating (VLR).&lt;br/&gt;&lt;br/&gt;

Typical unit code(s): KGM for kilogram, LBR for pound&lt;br/&gt;&lt;br/&gt;

&lt;ul&gt;
&lt;li&gt;Note 1: You can indicate additional information in the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/name&quot;&gt;name&lt;/a&gt; of the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QuantitativeValue&quot;&gt;QuantitativeValue&lt;/a&gt; node.&lt;/li&gt;
&lt;li&gt;Note 2: You may also link to a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QualitativeValue&quot;&gt;QualitativeValue&lt;/a&gt; node that provides additional information using &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/valueReference&quot;&gt;valueReference&lt;/a&gt;.&lt;/li&gt;
&lt;li&gt;Note 3: Note that you can use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/minValue&quot;&gt;minValue&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/maxValue&quot;&gt;maxValue&lt;/a&gt; to indicate ranges.&lt;/li&gt;
&lt;/ul&gt;

Predicate describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_value_for_tongue_weight_kg )
( #has_/range :: QuantitativeValue )

