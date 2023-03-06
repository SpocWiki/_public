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

title: has_text_about_gtin14
linkTitle: has_text_about_gtin14

keywords: [gtin14]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- gtin14
- gtin14
- gtin14
- has_text_about_gtin14
---

Predicate to describe the Text of Demand, Offer, Product.

Use it like this: 
- [ #has_/text/_about_gtin14 :: Text ] or 
- [ has_text_about_gtin14 :: Text ] 

The GTIN-14 code of the product, or the product to which the offer refers. See &lt;a href="http://www.gs1.org/barcodes/technical/idkeys/gtin"&gt;GS1 GTIN Summary&lt;/a&gt; for more details.

Predicated describes that: 
[ #has_/domain  :: Demand, Offer, Product ]
( #has_/name :: has_text_about_gtin14 )
( #has_/range :: Text )

[ #is_/sub_property_of  :: gtin, identifier ]

