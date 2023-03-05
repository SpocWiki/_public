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
title: has_energy_efficiency_scale_min

linkTitle: has_energy_efficiency_scale_min
keywords: [energy, efficiency, scale, min]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- energy-efficiency-scale-min
- energy_efficiency_scale_min
- energyEfficiencyScaleMin
- has_energy_efficiency_scale_min
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_energy_efficiency_scale_min :: EUEnergyEfficiencyEnumeration ] or 
- [ has_energy_efficiency_scale_min :: EUEnergyEfficiencyEnumeration ] 

Specifies the least energy efficient class on the regulated EU energy consumption scale for the product category a product belongs to. For example, energy consumption for televisions placed on the market after January 1, 2020 is scaled from D to A+++.

Relation describes that: 
[ #has_/domain  :: EnergyConsumptionDetails ]
( #has_/name :: is_energy_efficiency_scale_min )
( #has_/range :: EUEnergyEfficiencyEnumeration )

