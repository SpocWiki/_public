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

title: has_text_about_product_id
linkTitle: has_text_about_product_id

keywords: [product, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- product-id
- product_id
- productID
- has_text_about_product_id
---

Predicate to describe the Text of Product.

Use it like this: 
- [ #has_/text/_about_product_id :: Text ] or 
- [ has_text_about_product_id :: Text ] 

The product identifier, such as ISBN. For example: &lt;code&gt;meta itemprop&#x3D;&quot;productID&quot; content&#x3D;&quot;isbn:123-456-789&quot;&lt;/code&gt;.

Predicated describes that: 
[ #has_/domain  :: Product ]
( #has_/name :: is_product_id )
( #has_/range :: Text )

[ #is_/sub_property_of  :: identifier ]

