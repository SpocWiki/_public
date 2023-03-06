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

title: has_dose-schedule
linkTitle: has_dose-schedule

keywords: [dose-schedule]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Quantity

aliases:
- dose_schedule
- dose-schedule
- doseSchedule
- has_value_for_dose_schedule
---

Predicate to describe the Quantity of Drug, TherapeuticProcedure.

Use it like this: 
- [ #has_/value/_for_dose_schedule :: DoseSchedule ] or 
- [ has_value_for_dose_schedule :: DoseSchedule ] 

A dosing schedule for the drug for a given population, either observed, recommended, or maximum dose based on the type used.

Predicate describes that: 
[ #has_/domain  :: Drug, TherapeuticProcedure ]
( #has_/name :: has_value_for_dose_schedule )
( #has_/range :: DoseSchedule )

