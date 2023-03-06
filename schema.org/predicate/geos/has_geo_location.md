---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate geo
publish: true

# Hugo Tags
type: Pred_geo

title: has_geo_location_location
linkTitle: has_geo_location_location

keywords: [location]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/geo

aliases:
- location
- location
- location
- has_geo_location_location
---

Predicate to describe the geo of Action, Event, InteractionCounter, Organization.

[ #is_/part_of ::  ]

Use it like this: 
- [ #has_/geo/_location :: Place, PostalAddress, Text, VirtualLocation ] or 
- [ has_geo_location :: Place, PostalAddress, Text, VirtualLocation ] 

The location of, for example, where an event is happening, where an organization is located, or where an action takes place.

Predicate describes that: 
[ #has_/domain  :: Action, Event, InteractionCounter, Organization ]
( #has_/name :: has_geo_location_location )
( #has_/range :: Place, PostalAddress, Text, VirtualLocation )

[ #is_/inverse_of  ::  ]

[ #is_/sub_property_of  ::  ]

[ #has_/sub_properties :: [ course, entertainmentBusiness, exerciseCourse, foodEstablishment, foodEvent, fromLocation, homeLocation, itemLocation, sportsActivityLocation, sportsEvent, toLocation, workLocation ] ]

