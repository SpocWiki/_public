---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Url
publish: true

# Hugo Tags
type: Predi_Url

title: has_url_for_benefits_summary_url
linkTitle: has_url_for_benefits_summary_url

keywords: [benefits_summary_url]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Url

aliases:
- benefits-summary-url
- benefits_summary_url
- benefitsSummaryUrl
- has_url_for_benefits_summary_url
---

Predicate to specify the Url of HealthInsurancePlan.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/url/_for_benefits_summary_url :: URL ] or 
- [ has_url_for_benefits_summary_url :: URL ] 

The URL that goes directly to the summary of benefits and coverage for the specific standard plan or plan variation.

Predicate describes that: 
[ #has_/domain  :: HealthInsurancePlan ]
( #has_/name :: has_url_for_benefits_summary_url )
( #has_/range :: URL )

