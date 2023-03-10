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

title: has_fuel-efficiency
linkTitle: has_fuel-efficiency

keywords: [fuel-efficiency]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- fuel_efficiency
- fuel-efficiency
- fuelEfficiency
- has_value_for_fuel_efficiency
---

Predicate to describe the Quantity of Vehicle.

Use it like this: 
- [ #has_/value/_for_fuel_efficiency :: QuantitativeValue ] or 
- [ has_value_for_fuel_efficiency :: QuantitativeValue ] 

The distance traveled per unit of fuel used; most commonly miles per gallon (mpg) or kilometers per liter (km/L).&lt;br/&gt;&lt;br/&gt;

&lt;ul&gt;
&lt;li&gt;Note 1: There are unfortunately no standard unit codes for miles per gallon or kilometers per liter. Use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/unitText&quot;&gt;unitText&lt;/a&gt; to indicate the unit of measurement, e.g. mpg or km/L.&lt;/li&gt;
&lt;li&gt;Note 2: There are two ways of indicating the fuel consumption, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/fuelConsumption&quot;&gt;fuelConsumption&lt;/a&gt; (e.g. 8 liters per 100 km) and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/fuelEfficiency&quot;&gt;fuelEfficiency&lt;/a&gt; (e.g. 30 miles per gallon). They are reciprocal.&lt;/li&gt;
&lt;li&gt;Note 3: Often, the absolute value is useful only when related to driving speed (&quot;at 80 km/h&quot;) or usage pattern (&quot;city traffic&quot;). You can use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/valueReference&quot;&gt;valueReference&lt;/a&gt; to link the value for the fuel economy to another value.&lt;/li&gt;
&lt;/ul&gt;

Predicate describes that: 
[ #has_/domain  :: Vehicle ]
( #has_/name :: has_value_for_fuel_efficiency )
( #has_/range :: QuantitativeValue )

