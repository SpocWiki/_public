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

&lt;a class="localLink" href="/ArchiveOrganization"&gt;ArchiveOrganization&lt;/a&gt; that holds, keeps or maintains the &lt;a class="localLink" href="/ArchiveComponent"&gt;ArchiveComponent&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: ArchiveComponent]
( #has_/name :: is_holding_archive)
( #has_/range :: ArchiveOrganization)

[ #is_/inverse_of  :: archiveHeld]

