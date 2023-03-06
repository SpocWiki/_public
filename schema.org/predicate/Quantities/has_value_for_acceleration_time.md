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

title: has_acceleration-time
linkTitle: has_acceleration-time

keywords: [acceleration-time]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- acceleration_time
- acceleration-time
- accelerationTime
- has_value_for_acceleration_time
---

Predicate to describe the Quantity of Vehicle.

[ #is_/part_of :: https://auto.schema.org ]

Use it like this: 
- [ #has_/value/_for_acceleration_time :: QuantitativeValue ] or 
- [ has_value_for_acceleration_time :: QuantitativeValue ] 

The time needed to accelerate the vehicle from a given start velocity to a given target velocity.&lt;br/&gt;&lt;br/&gt;
Typical unit code(s): SEC for seconds&lt;br/&gt;&lt;br/&gt;
&lt;ul&gt;
&lt;li&gt;Note: There are unfortunately no standard unit codes for seconds/0..100 km/h or seconds/0..60 mph. Simply use &quot;SEC&quot; for seconds and indicate the velocities in the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/name&quot;&gt;name&lt;/a&gt; of the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QuantitativeValue&quot;&gt;QuantitativeValue&lt;/a&gt;, or use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/valueReference&quot;&gt;valueReference&lt;/a&gt; with a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/QuantitativeValue&quot;&gt;QuantitativeValue&lt;/a&gt; of 0..60 mph or 0..100 km/h to specify the reference speeds.&lt;/li&gt;
&lt;/ul&gt;

Predicate describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_value_for_acceleration_time )
( #has_/range :: QuantitativeValue )

