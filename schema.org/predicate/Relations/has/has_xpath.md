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
title: has_xpath

linkTitle: has_xpath
keywords: [xpath]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- xpath
- xpath
- xpath
- has_xpath
---

Use it like this: 
- [ #has/_xpath :: XPathType ] or 
- [ has_xpath :: XPathType ] 

An XPath, e.g. of a &lt;a class="localLink" href="/SpeakableSpecification"&gt;SpeakableSpecification&lt;/a&gt; or &lt;a class="localLink" href="/WebPageElement"&gt;WebPageElement&lt;/a&gt;. In the latter case, multiple matches within a page can constitute a single conceptual "Web page element".

Relation describes that: 
[ #has_/domain  :: SpeakableSpecification, WebPageElement ]
( #has_/name :: is_xpath )
( #has_/range :: XPathType )

