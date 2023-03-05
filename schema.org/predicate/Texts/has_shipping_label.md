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

title: has_text_about_shipping_label
linkTitle: has_text_about_shipping_label

keywords: [shipping, label]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- shipping-label
- shipping_label
- shippingLabel
- has_text_about_shipping_label
---

Predicate to describe the Text of OfferShippingDetails, ShippingRateSettings.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_shipping_label :: Text ] or 
- [ has_text_about_shipping_label :: Text ] 

Label to match an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/OfferShippingDetails&quot;&gt;OfferShippingDetails&lt;/a&gt; with a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ShippingRateSettings&quot;&gt;ShippingRateSettings&lt;/a&gt; (within the context of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/shippingSettingsLink&quot;&gt;shippingSettingsLink&lt;/a&gt; cross-reference).

Predicated describes that: 
[ #has_/domain  :: OfferShippingDetails, ShippingRateSettings ]
( #has_/name :: has_text_about_shipping_label )
( #has_/range :: Text )

