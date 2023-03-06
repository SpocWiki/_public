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

title: has_activity-frequency
linkTitle: has_activity-frequency

keywords: [activity-frequency]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Quantity

aliases:
- activity_frequency
- activity-frequency
- activityFrequency
- has_value_for_activity_frequency
---

Predicate to describe the Quantity of ExercisePlan.

Use it like this: 
- [ #has_/value/_for_activity_frequency :: QuantitativeValue, Text ] or 
- [ has_value_for_activity_frequency :: QuantitativeValue, Text ] 

How often one should engage in the activity.

Predicate describes that: 
[ #has_/domain  :: ExercisePlan ]
( #has_/name :: has_value_for_activity_frequency )
( #has_/range :: QuantitativeValue, Text )

