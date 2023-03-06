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
title: has_usage_info

linkTitle: has_usage_info
keywords: [usage, info]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- usage-info
- usage_info
- usageInfo
- has_usage_info
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_usage_info :: CreativeWork, URL ] or 
- [ has_usage_info :: CreativeWork, URL ] 

The schema.org &lt;a class="localLink" href="/usageInfo"&gt;usageInfo&lt;/a&gt; property indicates further information about a &lt;a class="localLink" href="/CreativeWork"&gt;CreativeWork&lt;/a&gt;. This property is applicable both to works that are freely available and to those that require payment or other transactions. It can reference additional information, e.g. community expectations on preferred linking and citation conventions, as well as purchasing details. For something that can be commercially licensed, usageInfo can provide detailed, resource-specific information about licensing options.&lt;br/&gt;&lt;br/&gt;

This property can be used alongside the license property which indicates license(s) applicable to some piece of content. The usageInfo property can provide information about other licensing options, e.g. acquiring commercial usage rights for an image that is also available under non-commercial creative commons licenses.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_usage_info )
( #has_/range :: CreativeWork, URL )

[ #has_/sub_properties :: [ acquireLicensePage ] ]

