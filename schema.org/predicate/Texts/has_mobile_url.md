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

title: has_text_about_mobile_url
linkTitle: has_text_about_mobile_url

keywords: [mobile, url]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- mobile-url
- mobile_url
- mobileUrl
- has_text_about_mobile_url
---

Predicate to describe the Text of Offer, Product.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_mobile_url :: Text ] or 
- [ has_text_about_mobile_url :: Text ] 

The &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/mobileUrl&quot;&gt;mobileUrl&lt;/a&gt; property is provided for specific situations in which data consumers need to determine whether one of several provided URLs is a dedicated "mobile site".&lt;br/&gt;&lt;br/&gt;

To discourage over-use, and reflecting intial usecases, the property is expected only on &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Product&quot;&gt;Product&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Offer&quot;&gt;Offer&lt;/a&gt;, rather than &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Thing&quot;&gt;Thing&lt;/a&gt;. The general trend in web technology is towards &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/Responsive_web_design&quot;&gt;responsive design&lt;/a&gt; in which content can be flexibly adapted to a wide range of browsing environments. Pages and sites referenced with the long-established &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/url&quot;&gt;url&lt;/a&gt; property should ideally also be usable on a wide variety of devices, including mobile phones. In most cases, it would be pointless and counter productive to attempt to update all &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/url&quot;&gt;url&lt;/a&gt; markup to use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/mobileUrl&quot;&gt;mobileUrl&lt;/a&gt; for more mobile-oriented pages. The property is intended for the case when items (primarily &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Product&quot;&gt;Product&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Offer&quot;&gt;Offer&lt;/a&gt;) have extra URLs hosted on an additional &quot;mobile site&quot; alongside the main one. It should not be taken as an endorsement of this publication style.

Predicated describes that: 
[ #has_/domain  :: Offer, Product ]
( #has_/name :: has_text_about_mobile_url )
( #has_/range :: Text )

