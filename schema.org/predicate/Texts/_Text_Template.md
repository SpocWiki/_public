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

title: has_text_about_{{label_snail}}
linkTitle: has_text_about_{{label_snail}}

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
- has_text_about_{{label_snail}}
---

Predicate to describe the Text of {{domainIncludes}}.

[ #is_/part_of :: {{isPartOf}} ]

Use it like this: 
- [ #has_/text/_about_{{label_snail}} :: {{rangeIncludes}} ] or 
- [ has_text_about_{{label_snail}} :: {{rangeIncludes}} ] 

{{comment}}

Predicated describes that: 
[ #has_/domain  :: {{domainIncludes}} ]
( #has_/name :: is_{{label_snail}} )
( #has_/range :: {{rangeIncludes}} )

[ #is_/inverse_of  :: {{inverseOf}} ]

[ #is_/sub_property_of  :: {{subPropertyOf}} ]

[ #has_/sub_properties :: [ {{subproperties}} ] ]

