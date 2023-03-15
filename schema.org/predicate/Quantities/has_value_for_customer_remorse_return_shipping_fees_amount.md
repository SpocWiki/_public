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

title: has_customer-remorse-return-shipping-fees-amount
linkTitle: has_customer-remorse-return-shipping-fees-amount

keywords: [customer-remorse-return-shipping-fees-amount]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Quantity

aliases:
- customer_remorse_return_shipping_fees_amount
- customer-remorse-return-shipping-fees-amount
- customerRemorseReturnShippingFeesAmount
- has_value_for_customer_remorse_return_shipping_fees_amount
---

Predicate to describe the Quantity of MerchantReturnPolicy.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_customer_remorse_return_shipping_fees_amount :: MonetaryAmount ] or 
- [ has_value_for_customer_remorse_return_shipping_fees_amount :: MonetaryAmount ] 

The amount of shipping costs if a product is returned due to customer remorse. Applicable when property [[customerRemorseReturnFees]] equals [[ReturnShippingFees]].

Predicate describes that: 
[ #has_/domain  :: MerchantReturnPolicy ]
( #has_/name :: has_value_for_customer_remorse_return_shipping_fees_amount )
( #has_/range :: MonetaryAmount )

