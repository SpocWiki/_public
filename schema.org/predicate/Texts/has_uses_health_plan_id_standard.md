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

title: has_text_about_uses_health_plan_id_standard
linkTitle: has_text_about_uses_health_plan_id_standard

keywords: [uses, health, plan, id, standard]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- uses-health-plan-id-standard
- uses_health_plan_id_standard
- usesHealthPlanIdStandard
- has_text_about_uses_health_plan_id_standard
---

Predicate to describe the Text of HealthInsurancePlan.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_uses_health_plan_id_standard :: Text, URL ] or 
- [ has_text_about_uses_health_plan_id_standard :: Text, URL ] 

The standard for interpreting the Plan ID. The preferred is &quot;HIOS&quot;. See the Centers for Medicare &amp;amp; Medicaid Services for more details.

Predicated describes that: 
[ #has_/domain  :: HealthInsurancePlan ]
( #has_/name :: has_text_about_uses_health_plan_id_standard )
( #has_/range :: Text, URL )

