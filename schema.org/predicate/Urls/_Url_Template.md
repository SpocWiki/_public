---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Url
publish: true

# Hugo Tags
type: Predi_Url

title: has_url_for_{{label_snail}}
linkTitle: has_url_for_{{label_snail}}

keywords: [{{label_snail}}]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: {{supersedes}}
superseded_by: {{supersededBy}}

tags:
- schema.org/Predicate/Url

aliases:
- {{label-dash}}
- {{label_snail}}
- {{label}}
- has_url_for_{{label_snail}}
---

Predicate to specify the Url of {{domainIncludes}}.

[ #is_/part_of :: {{isPartOf}} ]

Use it like this: 
- [ #has_/url/_for_{{label_snail}} :: {{rangeIncludes}} ] or 
- [ has_url_for_{{label_snail}} :: {{rangeIncludes}} ] 

{{comment}}

Predicate describes that: 
[ #has_/domain  :: {{domainIncludes}} ]
( #has_/name :: has_url_for_{{label_snail}} )
( #has_/range :: {{rangeIncludes}} )

[ #is_/inverse_of  :: {{inverseOf}} ]

[ #is_/sub_property_of  :: {{subPropertyOf}} ]

[ #has_/sub_properties :: [ {{subproperties}} ] ]

