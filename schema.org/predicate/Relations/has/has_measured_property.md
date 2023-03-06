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
title: has_measured_property

linkTitle: has_measured_property
keywords: [measured, property]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- measured-property
- measured_property
- measuredProperty
- has_measured_property
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_measured_property :: Property ] or 
- [ has_measured_property :: Property ] 

The measuredProperty of an &lt;a class="localLink" href="/Observation"&gt;Observation&lt;/a&gt;, either a schema.org property, a property from other RDF-compatible systems, e.g. W3C RDF Data Cube, or schema.org extensions such as &lt;a href="https://www.gs1.org/voc/?show=properties"&gt;GS1's&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Observation ]
( #has_/name :: is_measured_property )
( #has_/range :: Property )

