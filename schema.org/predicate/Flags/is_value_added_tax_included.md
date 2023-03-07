---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_value_added_tax_included
linkTitle: is_value_added_tax_included

keywords: [value_added_tax_included]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- value-added-tax-included
- value_added_tax_included
- valueAddedTaxIncluded
- is_value_added_tax_included
---

Use these simple Tags to mark Instances as True or False: 
#is_/_/value_added_tax_included 
#is_/not_/value_added_tax_included 

Or write it as a Triple: 
[ is_value_added_tax_included :: Boolean ] 

Specifies whether the applicable value-added tax (VAT) is included in the price specification or not.

Predicate describes that: 
[ #has_/domain  :: PriceSpecification ]
( #has_/name :: is_value_added_tax_included )
( #has_/range :: Boolean )

