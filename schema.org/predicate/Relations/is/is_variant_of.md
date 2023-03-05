---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: is_variant_of

linkTitle: is_variant_of
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- is-variant-of
- variant_of
- isVariantOf
- is_variant_of
---

[ #is_/part_of :: ]

Use it like this: 
- [ #is/_variant_of :: ProductGroup, ProductModel] or 
- [ is_variant_of :: ProductGroup, ProductModel] 

Indicates the kind of product that this is a variant of. In the case of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ProductModel&quot;&gt;ProductModel&lt;/a&gt;, this is a pointer (from a ProductModel) to a base product from which this product is a variant. It is safe to infer that the variant inherits all product features from the base model, unless defined locally. This is not transitive. In the case of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ProductGroup&quot;&gt;ProductGroup&lt;/a&gt;, the group description also serves as a template, representing a set of Products that vary on explicitly defined, specific dimensions only (so it defines both a set of variants, as well as which values distinguish amongst those variants). When used with &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ProductGroup&quot;&gt;ProductGroup&lt;/a&gt;, this property can apply to any &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Product&quot;&gt;Product&lt;/a&gt; included in the group.

Relation describes that: 
[ #has_/domain  :: Product, ProductModel]
( #has_/name :: is_variant_of)
( #has_/range :: ProductGroup, ProductModel)

[ #is_/inverse_of  :: hasVariant]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
