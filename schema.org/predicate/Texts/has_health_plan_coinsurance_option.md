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

title: has_text_about_health_plan_coinsurance_option
linkTitle: has_text_about_health_plan_coinsurance_option

keywords: [health, plan, coinsurance, option]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- health-plan-coinsurance-option
- health_plan_coinsurance_option
- healthPlanCoinsuranceOption
- has_text_about_health_plan_coinsurance_option
---

Predicate to describe the Text of HealthPlanCostSharingSpecification.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_health_plan_coinsurance_option :: Text ] or 
- [ has_text_about_health_plan_coinsurance_option :: Text ] 

Whether the coinsurance applies before or after deductible, etc. TODO: Is this a closed set?

Predicated describes that: 
[ #has_/domain  :: HealthPlanCostSharingSpecification ]
( #has_/name :: is_health_plan_coinsurance_option )
( #has_/range :: Text )

