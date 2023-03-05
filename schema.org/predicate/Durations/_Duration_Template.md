---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Duration
publish: true

# Hugo Tags
type: Predi_Duration
title: has_duration_of_{{label_snail}}

linkTitle: 
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/Durations

aliases:
- {{label-dash}}
- {{label_snail}}
- {{label}}
- has_duration_of_{{label_snail}}
---

Predicate to describe the Duration of {{domainIncludes}}.

[is_part_of:: {{isPartOf}}]

Use it like this: 
- [has_duration_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/duration/_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-Duration Format](../../../ISO/ISO_8601-Date_Time) .


{{comment}}

Formal Predicate: 
[domain::{{domainIncludes}}]
(name::has_duration_of_{{label_snail}})
(range::{{rangeIncludes}})

Is [sub_property_of::{{subPropertyOf}}]

Has [sub_properties::{{subproperties}}]
