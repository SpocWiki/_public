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

title: has_text_about_price_range
linkTitle: has_text_about_price_range

keywords: [price, range]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- price-range
- price_range
- priceRange
- has_text_about_price_range
---

Predicate to describe the Text of LocalBusiness.

Use it like this: 
- [ #has_/text/_about_price_range :: Text ] or 
- [ has_text_about_price_range :: Text ] 

The price range of the business, for example &lt;code&gt;$$$&lt;/code&gt;.

Predicated describes that: 
[ #has_/domain  :: LocalBusiness ]
( #has_/name :: is_price_range )
( #has_/range :: Text )

