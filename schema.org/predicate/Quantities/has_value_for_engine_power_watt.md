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

title: has_engine-power
linkTitle: has_engine-power

keywords: [engine-power]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- engine_power
- engine-power
- enginePower
- has_value_for_engine_power_watt
---

Predicate to describe the Quantity of EngineSpecification.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_engine_power_watt :: QuantitativeValue ] or 
- [ has_value_for_engine_power_watt :: QuantitativeValue ] 

The power of the vehicle&#x27;s engine.
    Typical unit code(s): KWT for kilowatt, BHP for brake horsepower, N12 for metric horsepower (PS, with 1 PS &#x3D; 735,49875 W)&lt;br/&gt;&lt;br/&gt;

&lt;ul&gt;
&lt;li&gt;Note 1: There are many different ways of measuring an engine&#x27;s power. For an overview, see  &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/Horsepower#Engine_power_test_codes&quot;&gt;http://en.wikipedia.org/wiki/Horsepower#Engine_power_test_codes&lt;/a&gt;.&lt;/li&gt;
&lt;li&gt;Note 2: You can link to information about how the given value has been determined using the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/valueReference&quot;&gt;valueReference&lt;/a&gt; property.&lt;/li&gt;
&lt;li&gt;Note 3: You can use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/minValue&quot;&gt;minValue&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/maxValue&quot;&gt;maxValue&lt;/a&gt; to indicate ranges.&lt;/li&gt;
&lt;/ul&gt;

Predicate describes that: 
[ #has_/domain  :: EngineSpecification ]
( #has_/name :: has_value_for_engine_power_watt )
( #has_/range :: QuantitativeValue )

