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

title: has_text_about_cvd_facility_id
linkTitle: has_text_about_cvd_facility_id

keywords: [cvd, facility, id]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- cvd-facility-id
- cvd_facility_id
- cvdFacilityId
- has_text_about_cvd_facility_id
---

Predicate to describe the Text of CDCPMDRecord.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_cvd_facility_id :: Text ] or 
- [ has_text_about_cvd_facility_id :: Text ] 

Identifier of the NHSN facility that this data record applies to. Use [[cvdFacilityCounty]] to indicate the county. To provide other details, [[healthcareReportingData]] can be used on a [[Hospital]] entry.

Predicated describes that: 
[ #has_/domain  :: CDCPMDRecord ]
( #has_/name :: has_text_about_cvd_facility_id )
( #has_/range :: Text )

