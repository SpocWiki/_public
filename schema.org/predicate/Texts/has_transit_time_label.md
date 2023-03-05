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

title: has_text_about_transit_time_label
linkTitle: has_text_about_transit_time_label

keywords: [transit, time, label]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- transit-time-label
- transit_time_label
- transitTimeLabel
- has_text_about_transit_time_label
---

Predicate to describe the Text of DeliveryTimeSettings, OfferShippingDetails.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_transit_time_label :: Text ] or 
- [ has_text_about_transit_time_label :: Text ] 

Label to match an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/OfferShippingDetails&quot;&gt;OfferShippingDetails&lt;/a&gt; with a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/DeliveryTimeSettings&quot;&gt;DeliveryTimeSettings&lt;/a&gt; (within the context of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/shippingSettingsLink&quot;&gt;shippingSettingsLink&lt;/a&gt; cross-reference).

Predicated describes that: 
[ #has_/domain  :: DeliveryTimeSettings, OfferShippingDetails ]
( #has_/name :: has_text_about_transit_time_label )
( #has_/range :: Text )

