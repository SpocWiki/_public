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
title: is_holding_archive

linkTitle: is_holding_archive
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- holding-archive
- holding_archive
- holdingArchive
- is_holding_archive
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #is/_holding_archive :: ArchiveOrganization] or 
- [ is_holding_archive :: ArchiveOrganization] 

[[ArchiveOrganization]] that holds, keeps or maintains the [[ArchiveComponent]].

Relation describes that: 
[ #has_/domain  :: ArchiveComponent]
( #has_/name :: is_holding_archive)
( #has_/range :: ArchiveOrganization)

[ #is_/inverse_of  :: archiveHeld]

