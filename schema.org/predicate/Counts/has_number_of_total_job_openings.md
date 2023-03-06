---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Count
publish: true

# Hugo Tags
type: Predi_Count

title: has_number_of_total_job_openings
linkTitle: has_number_of_total_job_openings

keywords: [total_job_openings]
layout: 
draft: false
publishDate:
expiryDate: 


tags:
- schema.org/Predicate/Count

aliases:
- total-job-openings
- total_job_openings
- totalJobOpenings
- has_number_of_total_job_openings
---

Predicate to describe the Number of JobPosting.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/number/_of_total_job_openings :: Integer ] or 
- [ has_number_of_total_job_openings :: Integer ] 

The number of positions open for this job posting. Use a positive integer. Do not use if the number of positions is unclear or not known.

Predicate describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: has_number_of_total_job_openings )
( #has_/range :: Integer )

