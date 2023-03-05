---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_value_reference

linkTitle: has_value_reference
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- value-reference
- value_reference
- valueReference
- has_value_reference
---

[ #is_/part_of :: ]

Use it like this: 
- [ #has/_value_reference :: DefinedTerm, Enumeration, MeasurementTypeEnumeration, PropertyValue, QualitativeValue, QuantitativeValue, StructuredValue, Text] or 
- [ has_value_reference :: DefinedTerm, Enumeration, MeasurementTypeEnumeration, PropertyValue, QualitativeValue, QuantitativeValue, StructuredValue, Text] 

A secondary value that provides additional information on the original value, e.g. a reference temperature or a type of measurement.

Relation describes that: 
[ #has_/domain  :: PropertyValue, QualitativeValue, QuantitativeValue]
( #has_/name :: is_value_reference)
( #has_/range :: DefinedTerm, Enumeration, MeasurementTypeEnumeration, PropertyValue, QualitativeValue, QuantitativeValue, StructuredValue, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

