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

title: has_text_about_health_plan_drug_tier
linkTitle: has_text_about_health_plan_drug_tier

keywords: [health, plan, drug, tier]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- health-plan-drug-tier
- health_plan_drug_tier
- healthPlanDrugTier
- has_text_about_health_plan_drug_tier
---

Predicate to describe the Text of HealthInsurancePlan, HealthPlanFormulary.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_health_plan_drug_tier :: Text ] or 
- [ has_text_about_health_plan_drug_tier :: Text ] 

The tier(s) of drugs offered by this formulary or insurance plan.

Predicated describes that: 
[ #has_/domain  :: HealthInsurancePlan, HealthPlanFormulary ]
( #has_/name :: is_health_plan_drug_tier )
( #has_/range :: Text )

