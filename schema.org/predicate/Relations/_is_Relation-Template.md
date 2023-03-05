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
title: {{has_label_snail}}

linkTitle: 
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
- {{has_label_snail}}
---

[is_part_of:: {{isPartOf}}]

Use it like this: 
- [has_duration_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .


{{comment}}

Predicate describes that: 
[domain::{{domainIncludes}}]
(name::{{has_label_snail}})
(range::{{rangeIncludes}})

Is [inverse_of::{{inverseOf}}]
Is [sub_property_of::{{subPropertyOf}}]
Has [sub_properties::{{subproperties}}]

