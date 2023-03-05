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
title: has_participant

linkTitle: has_participant
keywords: [participant]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- participant
- participant
- participant
- has_participant
---

Use it like this: 
- [ #has/_participant :: Organization, Person ] or 
- [ has_participant :: Organization, Person ] 

Other co-agents that participated in the action indirectly. E.g. John wrote a book with &lt;em&gt;Steve&lt;/em&gt;.

Relation describes that: 
[ #has_/domain  :: Action ]
( #has_/name :: is_participant )
( #has_/range :: Organization, Person )

[ #has_/sub_properties :: [ borrower, buyer, endorsee, landlord, lender, loser, opponent, realEstateAgent, recipient, seller, sender, sportsTeam, vendor, winner ] ]

