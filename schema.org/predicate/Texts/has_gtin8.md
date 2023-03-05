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

title: has_text_about_gtin8
linkTitle: has_text_about_gtin8

keywords: [gtin8]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- gtin8
- gtin8
- gtin8
- has_text_about_gtin8
---

Predicate to describe the Text of Demand, Offer, Product.

Use it like this: 
- [ #has_/text/_about_gtin8 :: Text ] or 
- [ has_text_about_gtin8 :: Text ] 

The GTIN-8 code of the product, or the product to which the offer refers. This code is also known as EAN/UCC-8 or 8-digit EAN. See &lt;a href&#x3D;&quot;http://www.gs1.org/barcodes/technical/idkeys/gtin&quot;&gt;GS1 GTIN Summary&lt;/a&gt; for more details.

Predicated describes that: 
[ #has_/domain  :: Demand, Offer, Product ]
( #has_/name :: is_gtin8 )
( #has_/range :: Text )

[ #is_/sub_property_of  :: gtin, identifier ]

