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

title: has_url_for_shipping_settings_link
linkTitle: has_url_for_shipping_settings_link

keywords: [shipping_settings_link]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Url

aliases:
- shipping-settings-link
- shipping_settings_link
- shippingSettingsLink
- has_url_for_shipping_settings_link
---

Predicate to specify the Url of OfferShippingDetails.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/url/_for_shipping_settings_link :: URL ] or 
- [ has_url_for_shipping_settings_link :: URL ] 

Link to a page containing &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ShippingRateSettings&quot;&gt;ShippingRateSettings&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/DeliveryTimeSettings&quot;&gt;DeliveryTimeSettings&lt;/a&gt; details.

Predicate describes that: 
[ #has_/domain  :: OfferShippingDetails ]
( #has_/name :: has_url_for_shipping_settings_link )
( #has_/range :: URL )

