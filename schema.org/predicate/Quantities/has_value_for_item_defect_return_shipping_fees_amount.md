---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Quantity
publish: true

# Hugo Tags
type: Predi_Quantity

title: has_item-defect-return-shipping-fees-amount
linkTitle: has_item-defect-return-shipping-fees-amount

keywords: [item-defect-return-shipping-fees-amount]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- item_defect_return_shipping_fees_amount
- item-defect-return-shipping-fees-amount
- itemDefectReturnShippingFeesAmount
- has_value_for_item_defect_return_shipping_fees_amount
---

Predicate to describe the Quantity of MerchantReturnPolicy.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_item_defect_return_shipping_fees_amount :: MonetaryAmount ] or 
- [ has_value_for_item_defect_return_shipping_fees_amount :: MonetaryAmount ] 

Amount of shipping costs for defect product returns. Applicable when property &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/itemDefectReturnFees&quot;&gt;itemDefectReturnFees&lt;/a&gt; equals &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/ReturnShippingFees&quot;&gt;ReturnShippingFees&lt;/a&gt;.

Predicate describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: has_value_for_item_defect_return_shipping_fees_amount )
( #has_/range :: MonetaryAmount )

