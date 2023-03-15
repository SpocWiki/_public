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

title: has_url_for_getting_tested_info
linkTitle: has_url_for_getting_tested_info

keywords: [getting_tested_info]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Url

aliases:
- getting-tested-info
- getting_tested_info
- gettingTestedInfo
- has_url_for_getting_tested_info
---

Predicate to specify the Url of SpecialAnnouncement.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/url/_for_getting_tested_info :: URL, WebContent ] or 
- [ has_url_for_getting_tested_info :: URL, WebContent ] 

Information about getting tested (for a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MedicalCondition&quot;&gt;MedicalCondition&lt;/a&gt;), e.g. in the context of a pandemic.

Predicate describes that: 
[ #has_/domain  :: SpecialAnnouncement ]
( #has_/name :: has_url_for_getting_tested_info )
( #has_/range :: URL, WebContent )

