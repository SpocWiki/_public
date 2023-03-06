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

title: has_exchange-rate-spread
linkTitle: has_exchange-rate-spread

keywords: [exchange-rate-spread]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- exchange_rate_spread
- exchange-rate-spread
- exchangeRateSpread
- has_value_for_exchange_rate_spread
---

Predicate to describe the Quantity of ExchangeRateSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/value/_for_exchange_rate_spread :: MonetaryAmount, Number ] or 
- [ has_value_for_exchange_rate_spread :: MonetaryAmount, Number ] 

The difference between the price at which a broker or other intermediary buys and sells foreign currency.

Predicate describes that: 
[ #has_/domain  :: ExchangeRateSpecification ]
( #has_/name :: has_value_for_exchange_rate_spread )
( #has_/range :: MonetaryAmount, Number )

