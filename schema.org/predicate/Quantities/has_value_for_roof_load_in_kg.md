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

title: has_roof-load
linkTitle: has_roof-load

keywords: [roof-load]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- roof_load
- roof-load
- roofLoad
- has_value_for_roof_load_in_kg
---

Predicate to describe the Quantity of BusOrCoach, Car.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_roof_load_in_kg :: QuantitativeValue ] or 
- [ has_value_for_roof_load_in_kg :: QuantitativeValue ] 

The permitted total weight of cargo and installations (e.g. a roof rack) on top of the vehicle.&lt;br/&gt;&lt;br/&gt;

Typical unit code(s): KGM for kilogram, LBR for pound&lt;br/&gt;&lt;br/&gt;

&lt;ul&gt;
&lt;li&gt;Note 1: You can indicate additional information in the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/name&quot;&gt;name&lt;/a&gt; of the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QuantitativeValue&quot;&gt;QuantitativeValue&lt;/a&gt; node.&lt;/li&gt;
&lt;li&gt;Note 2: You may also link to a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QualitativeValue&quot;&gt;QualitativeValue&lt;/a&gt; node that provides additional information using &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/valueReference&quot;&gt;valueReference&lt;/a&gt;&lt;/li&gt;
&lt;li&gt;Note 3: Note that you can use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/minValue&quot;&gt;minValue&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/maxValue&quot;&gt;maxValue&lt;/a&gt; to indicate ranges.&lt;/li&gt;
&lt;/ul&gt;

Predicate describes that: 
[ #has_/domain  :: BusOrCoach, Car ]
( #has_/name :: has_value_for_roof_load_in_kg )
( #has_/range :: QuantitativeValue )

