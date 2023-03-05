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
title: has_accepted_payment_method

linkTitle: has_accepted_payment_method
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
- accepted-payment-method
- accepted_payment_method
- acceptedPaymentMethod
- has_accepted_payment_method
---

Use it like this: 
- [ #has/_accepted_payment_method :: LoanOrCredit, PaymentMethod] or 
- [ has_accepted_payment_method :: LoanOrCredit, PaymentMethod] 

The payment method(s) accepted by seller for this offer.

Relation describes that: 
[ #has_/domain  :: Demand, Offer]
( #has_/name :: is_accepted_payment_method)
( #has_/range :: LoanOrCredit, PaymentMethod)

