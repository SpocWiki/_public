---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_healthcare_reporting_data

linkTitle: has_healthcare_reporting_data
keywords: [healthcare, reporting, data]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- healthcare-reporting-data
- healthcare_reporting_data
- healthcareReportingData
- has_healthcare_reporting_data
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_healthcare_reporting_data :: CDCPMDRecord, Dataset ] or 
- [ has_healthcare_reporting_data :: CDCPMDRecord, Dataset ] 

Indicates data describing a hospital, e.g. a CDC [[CDCPMDRecord]] or as some kind of [[Dataset]].

Relation describes that: 
[ #has_/domain  :: Hospital ]
( #has_/name :: has_healthcare_reporting_data )
( #has_/range :: CDCPMDRecord, Dataset )

