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

title: is_drive_through_service
linkTitle: is_drive_through_service

keywords: [drive_through_service]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- drive-through-service
- drive_through_service
- hasDriveThroughService
- is_drive_through_service
---

[ #is_/part_of :: pending: ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/drive_through_service 
#is_/not_/drive_through_service 

Or write it as a Triple: 
[ is_drive_through_service :: Boolean ] 

Indicates whether some facility (e.g. &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/FoodEstablishment&quot;&gt;FoodEstablishment&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CovidTestingFacility&quot;&gt;CovidTestingFacility&lt;/a&gt;) offers a service that can be used by driving through in a car. In the case of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CovidTestingFacility&quot;&gt;CovidTestingFacility&lt;/a&gt; such facilities could potentially help with social distancing from other potentially-infected users.

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: is_drive_through_service )
( #has_/range :: Boolean )

