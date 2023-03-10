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

title: has_text_about_accommodation_category
linkTitle: has_text_about_accommodation_category

keywords: [accommodation, category]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- accommodation-category
- accommodation_category
- accommodationCategory
- has_text_about_accommodation_category
---

Predicate to describe the Text of Accommodation.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_accommodation_category :: Text ] or 
- [ has_text_about_accommodation_category :: Text ] 

Category of an &lt;a class="localLink" href="/Accommodation"&gt;Accommodation&lt;/a&gt;, following real estate conventions, e.g. RESO (see &lt;a href="https://ddwiki.reso.org/display/DDW17/PropertySubType+Field"&gt;PropertySubType&lt;/a&gt;, and &lt;a href="https://ddwiki.reso.org/display/DDW17/PropertyType+Field"&gt;PropertyType&lt;/a&gt; fields  for suggested values).

Predicated describes that: 
[ #has_/domain  :: Accommodation ]
( #has_/name :: has_text_about_accommodation_category )
( #has_/range :: Text )

[ #is_/sub_property_of  :: category ]

