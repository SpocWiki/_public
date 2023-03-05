---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_{{label_snail}}
linkTitle: has_{{label_snail}}
keywords: [{{label_snail}}]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/Text

aliases:
- {{label-dash}}
- {{label_snail}}
- {{label}}
- has_{{label_snail}}
---

[ #is_/part_of :: {{isPartOf}} ]

Use it like this: 
- [ #has/_{{label_snail}} :: {{rangeIncludes}} ] or 
- [ has_{{label_snail}} :: {{rangeIncludes}} ] 

{{comment}}

Relation describes that: 
[ #has_/domain  :: {{domainIncludes}} ]
( #has_/name :: is_{{label_snail}} )
( #has_/range :: {{rangeIncludes}} )

[ #is_/inverse_of  :: {{inverseOf}} ]

[ #is_/sub_property_of  :: {{subPropertyOf}} ]

[ #has_/sub_properties :: [ {{subproperties}} ] ]

