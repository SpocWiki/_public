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
keywords: [maintainer]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- maintainer
- maintainer
- maintainer
- has_maintainer
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_maintainer :: Organization, Person ] or 
- [ has_maintainer :: Organization, Person ] 

A maintainer of a &lt;a class="localLink" href="/Dataset"&gt;Dataset&lt;/a&gt;, software package (&lt;a class="localLink" href="/SoftwareApplication"&gt;SoftwareApplication&lt;/a&gt;), or other &lt;a class="localLink" href="/Project"&gt;Project&lt;/a&gt;. A maintainer is a &lt;a class="localLink" href="/Person"&gt;Person&lt;/a&gt; or &lt;a class="localLink" href="/Organization"&gt;Organization&lt;/a&gt; that manages contributions to, and/or publication of, some (typically complex) artifact. It is common for distributions of software and data to be based on "upstream" sources. When &lt;a class="localLink" href="/maintainer"&gt;maintainer&lt;/a&gt; is applied to a specific version of something e.g. a particular version or packaging of a &lt;a class="localLink" href="/Dataset"&gt;Dataset&lt;/a&gt;, it is always  possible that the upstream source has a different maintainer. The &lt;a class="localLink" href="/isBasedOn"&gt;isBasedOn&lt;/a&gt; property can be used to indicate such relationships between datasets to make the different maintenance roles clear. Similarly in the case of software, a package may have dedicated maintainers working on integration into software distributions such as Ubuntu, as well as upstream maintainers of the underlying work.

Relation describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_maintainer )
( #has_/range :: Organization, Person )

