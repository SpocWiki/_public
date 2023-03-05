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
title: has_current_exchange_rate

linkTitle: has_current_exchange_rate
keywords: [current, exchange, rate]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- current-exchange-rate
- current_exchange_rate
- currentExchangeRate
- has_current_exchange_rate
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_current_exchange_rate :: UnitPriceSpecification ] or 
- [ has_current_exchange_rate :: UnitPriceSpecification ] 

The current price of a currency.

Relation describes that: 
[ #has_/domain  :: ExchangeRateSpecification ]
( #has_/name :: is_current_exchange_rate )
( #has_/range :: UnitPriceSpecification )

