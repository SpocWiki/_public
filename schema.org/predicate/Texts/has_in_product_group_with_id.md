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

title: has_text_about_in_product_group_with_id
linkTitle: has_text_about_in_product_group_with_id

keywords: [in, product, group, with, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- in-product-group-with-id
- in_product_group_with_id
- inProductGroupWithID
- has_text_about_in_product_group_with_id
---

Predicate to describe the Text of Product.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_in_product_group_with_id :: Text ] or 
- [ has_text_about_in_product_group_with_id :: Text ] 

Indicates the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/productGroupID&quot;&gt;productGroupID&lt;/a&gt; for a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ProductGroup&quot;&gt;ProductGroup&lt;/a&gt; that this product &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/isVariantOf&quot;&gt;isVariantOf&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: Product ]
( #has_/name :: is_in_product_group_with_id )
( #has_/range :: Text )

