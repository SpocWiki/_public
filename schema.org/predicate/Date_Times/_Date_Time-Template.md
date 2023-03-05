---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Date_Time
publish: true

# Hugo Tags
type: Predi_Date_Time
title: has_date_of_{{label_snail}}

linkTitle: has_date_of_{{label_snail}}
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/Date

aliases:
- {{label-dash}}
- {{label_snail}}
- {{label}}
- has_date_of_{{label_snail}}
---

Predicate to describe the date of {{domainIncludes}}.

[is_part_of:: {{isPartOf}}]

Use it like this: 
- [has_date_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] or 
- [ #has_/date/_of_{{label_snail}}::P#Y#M#W#DT#H#M#s.fff] with the [ISO_8601-date Format](../../../ISO/ISO_8601-Date_Time) .


{{comment}}

Formal Predicate: 
[domain::{{domainIncludes}}]
(name::has_date_of_{{label_snail}})
(range::{{rangeIncludes}})

Is [sub_property_of::{{subPropertyOf}}]

Has [sub_properties::{{subproperties}}]
