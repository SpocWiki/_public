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
title: has_maintainer

linkTitle: has_maintainer
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- maintainer
- maintainer
- maintainer
- has_maintainer
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_maintainer :: Organization, Person] or 
- [ has_maintainer :: Organization, Person] 

A maintainer of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Dataset&quot;&gt;Dataset&lt;/a&gt;, software package (&lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/SoftwareApplication&quot;&gt;SoftwareApplication&lt;/a&gt;), or other &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Project&quot;&gt;Project&lt;/a&gt;. A maintainer is a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Person&quot;&gt;Person&lt;/a&gt; or &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Organization&quot;&gt;Organization&lt;/a&gt; that manages contributions to, and/or publication of, some (typically complex) artifact. It is common for distributions of software and data to be based on &quot;upstream&quot; sources. When &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/maintainer&quot;&gt;maintainer&lt;/a&gt; is applied to a specific version of something e.g. a particular version or packaging of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Dataset&quot;&gt;Dataset&lt;/a&gt;, it is always  possible that the upstream source has a different maintainer. The &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/isBasedOn&quot;&gt;isBasedOn&lt;/a&gt; property can be used to indicate such relationships between datasets to make the different maintenance roles clear. Similarly in the case of software, a package may have dedicated maintainers working on integration into software distributions such as Ubuntu, as well as upstream maintainers of the underlying work.

Relation describes that: 
[ #has_/domain  :: CreativeWork]
( #has_/name :: is_maintainer)
( #has_/range :: Organization, Person)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]

