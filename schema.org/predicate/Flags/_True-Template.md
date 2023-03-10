---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_{{has_label_snail}}
linkTitle: is_{{has_label_snail}}

keywords: [{{has_label_snail}}]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/True

aliases:
- {{label-dash}}
- {{has_label_snail}}
- {{label}}
- is_{{has_label_snail}}
---

[ #is_/part_of :: {{isPartOf}} ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/{{has_label_snail}} 
#is_/not_/{{has_label_snail}} 

Or write it as a Triple: 
[ is_{{has_label_snail}} :: {{rangeIncludes}} ] 

{{comment}}

Predicate describes that: 
[ #has_/domain  :: {{domainIncludes}} ]
( #has_/name :: is_{{has_label_snail}} )
( #has_/range :: {{rangeIncludes}} )

[ #is_/inverse_of  :: {{inverseOf}} ]

[ #is_/sub_property_of  :: {{subPropertyOf}} ]

[ #has_/sub_properties :: [ {{subproperties}} ] ]

