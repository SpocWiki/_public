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

title: has_text_about_gtin
linkTitle: has_text_about_gtin

keywords: [gtin]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- gtin
- gtin
- gtin
- has_text_about_gtin
---

Predicate to describe the Text of Demand, Offer, Product.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_gtin :: Text, URL ] or 
- [ has_text_about_gtin :: Text, URL ] 

A Global Trade Item Number (&lt;a href&#x3D;&quot;https://www.gs1.org/standards/id-keys/gtin&quot;&gt;GTIN&lt;/a&gt;). GTINs identify trade items, including products and services, using numeric identification codes.&lt;br/&gt;&lt;br/&gt;

The GS1 &lt;a href&#x3D;&quot;https://www.gs1.org/standards/Digital-Link/&quot;&gt;digital link specifications&lt;/a&gt; express GTINs as URLs (URIs, IRIs, etc.). Details including regular expression examples can be found in, Section 6 of the GS1 URI Syntax specification; see also &lt;a href&#x3D;&quot;https://github.com/schemaorg/schemaorg/issues/3156#issuecomment-1209522809&quot;&gt;schema.org tracking issue&lt;/a&gt; for schema.org-specific discussion. A correct &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin&quot;&gt;gtin&lt;/a&gt; value should be a valid GTIN, which means that it should be an all-numeric string of either 8, 12, 13 or 14 digits, or a &quot;GS1 Digital Link&quot; URL based on such a string. The numeric component should also have a &lt;a href&#x3D;&quot;https://www.gs1.org/services/check-digit-calculator&quot;&gt;valid GS1 check digit&lt;/a&gt; and meet the other rules for valid GTINs. See also &lt;a href&#x3D;&quot;http://www.gs1.org/barcodes/technical/idkeys/gtin&quot;&gt;GS1"s GTIN Summary&lt;/a&gt; and &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/Global_Trade_Item_Number&quot;&gt;Wikipedia&lt;/a&gt; for more details. Left-padding of the gtin values is not required or encouraged. The &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin&quot;&gt;gtin&lt;/a&gt; property generalizes the earlier &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin8&quot;&gt;gtin8&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin12&quot;&gt;gtin12&lt;/a&gt;, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin13&quot;&gt;gtin13&lt;/a&gt;, and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/gtin14&quot;&gt;gtin14&lt;/a&gt; properties.&lt;br/&gt;&lt;br/&gt;

Note also that this is a definition for how to include GTINs in Schema.org data, and not a definition of GTINs in general - see the GS1 documentation for authoritative details.

Predicated describes that: 
[ #has_/domain  :: Demand, Offer, Product ]
( #has_/name :: is_gtin )
( #has_/range :: Text, URL )

[ #is_/sub_property_of  :: identifier ]

[ #has_/sub_properties :: [ gtin12, gtin13, gtin14, gtin8 ] ]

