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
title: is_{{label_snail}}

linkTitle: is_{{label_snail}}
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/Relation

aliases:
- {{label-dash}}
- {{label_snail}}
- {{label}}
- is_{{label_snail}}
---

[ #is_/part_of :: {{isPartOf}}]

Use it like this: 
- [ #is/_{{label_snail}} :: {{rangeIncludes}}] or 
- [ is_{{label_snail}} :: {{rangeIncludes}}] 

{{comment}}

Relation describes that: 
[ #has_/domain  :: {{domainIncludes}}]
( #has_/name :: is_{{label_snail}})
( #has_/range :: {{rangeIncludes}})

[ #is_/inverse_of  :: {{inverseOf}}]

[ #is_/sub_property_of  :: {{subPropertyOf}}]

[ #has_/sub_properties :: {{subproperties}}]

