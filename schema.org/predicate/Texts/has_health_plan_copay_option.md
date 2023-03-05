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

title: has_text_about_health_plan_copay_option
linkTitle: has_text_about_health_plan_copay_option

keywords: [health, plan, copay, option]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- health-plan-copay-option
- health_plan_copay_option
- healthPlanCopayOption
- has_text_about_health_plan_copay_option
---

Predicate to describe the Text of HealthPlanCostSharingSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_health_plan_copay_option :: Text ] or 
- [ has_text_about_health_plan_copay_option :: Text ] 

Whether the copay is before or after deductible, etc. TODO: Is this a closed set?

Predicated describes that: 
[ #has_/domain  :: HealthPlanCostSharingSpecification ]
( #has_/name :: has_text_about_health_plan_copay_option )
( #has_/range :: Text )

