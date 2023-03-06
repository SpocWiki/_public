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

title: is_public_access
linkTitle: is_public_access

keywords: [public_access]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- public-access
- public_access
- publicAccess
- is_public_access
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/public_access 
#is_/not/public_access 

Or write it as a Triple: 
[ is_public_access :: Boolean ] 

A flag to signal that the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Place&quot;&gt;Place&lt;/a&gt; is open to public visitors.  If this property is omitted there is no assumed default boolean value

Predicate describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: is_public_access )
( #has_/range :: Boolean )

