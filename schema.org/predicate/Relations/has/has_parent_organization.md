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
title: has_parent_organization

linkTitle: has_parent_organization
keywords: [parent, organization]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: branchOf
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- parent-organization
- parent_organization
- parentOrganization
- has_parent_organization
---

Use it like this: 
- [ #has/_parent_organization :: Organization ] or 
- [ has_parent_organization :: Organization ] 

The larger organization that this organization is a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/subOrganization&quot;&gt;subOrganization&lt;/a&gt; of, if any.

Relation describes that: 
[ #has_/domain  :: Organization ]
( #has_/name :: is_parent_organization )
( #has_/range :: Organization )

[ #is_/inverse_of  :: subOrganization ]

