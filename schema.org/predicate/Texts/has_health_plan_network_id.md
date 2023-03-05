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

title: has_text_about_health_plan_network_id
linkTitle: has_text_about_health_plan_network_id

keywords: [health, plan, network, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- health-plan-network-id
- health_plan_network_id
- healthPlanNetworkId
- has_text_about_health_plan_network_id
---

Predicate to describe the Text of HealthPlanNetwork, MedicalOrganization.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_health_plan_network_id :: Text ] or 
- [ has_text_about_health_plan_network_id :: Text ] 

Name or unique ID of network. (Networks are often reused across different insurance plans.)

Predicated describes that: 
[ #has_/domain  :: HealthPlanNetwork, MedicalOrganization ]
( #has_/name :: is_health_plan_network_id )
( #has_/range :: Text )

