---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Type
publish: true

# Hugo Tags
type: Type

title: is_a_defined_region Class
linkTitle: is_a_defined_region Class

keywords: [defined_region]
layout: 
draft: false
publishDate:
expiryDate: 

enumerationtype: 
equivalent_class: 

supersedes: 
superseded_by: 

tags:
- schema.org/Type

aliases:
- defined-region
- defined_region
- DefinedRegion
- is_a_defined_region
---

Class of all defined_regions.
Tag Instances like this: 
#is_/a_/defined_region

[ #is_/part_of :: https://pending.schema.org ]

A DefinedRegion is a geographic area defined by potentially arbitrary (rather than political, administrative or natural geographical) criteria. Properties are provided for defining a region by reference to sets of postal codes.<br/><br/>
Examples: a delivery destination when shopping. Region where regional pricing is configured.<br/><br/>
Requirement 1:
Country: US
States: "NY", "CA"<br/><br/>
Requirement 2:
Country: US
PostalCode Set: { [94000-94585], [97000, 97999], [13000, 13599]}
{ [12345, 12345], [78945, 78945], }
Region = state, canton, prefecture, autonomous community...

[ #is_/sub_class_of :: [[StructuredValue]] ]

[ #has_/properties :: [ additionalType, addressCountry, addressRegion, alternateName, description, disambiguatingDescription, identifier, image, mainEntityOfPage, name, postalCode, postalCodePrefix, postalCodeRange, potentialAction, sameAs, subjectOf, url ] ]

