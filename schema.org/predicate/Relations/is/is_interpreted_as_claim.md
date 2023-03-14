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
title: is_interpreted_as_claim

linkTitle: is_interpreted_as_claim
keywords: [interpreted, as, claim]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- interpreted-as-claim
- interpreted_as_claim
- interpretedAsClaim
- is_interpreted_as_claim
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #is/_interpreted_as_claim :: Claim ] or 
- [ is_interpreted_as_claim :: Claim ] 

Used to indicate a specific claim contained, implied, translated or refined from the content of a &lt;a class="localLink" href="/MediaObject"&gt;MediaObject&lt;/a&gt; or other &lt;a class="localLink" href="/CreativeWork"&gt;CreativeWork&lt;/a&gt;. The interpreting party can be indicated using &lt;a class="localLink" href="/claimInterpreter"&gt;claimInterpreter&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: CreativeWork, MediaObject ]
( #has_/name :: is_interpreted_as_claim )
( #has_/range :: Claim )

[ #is_/sub_property_of  :: description ]

