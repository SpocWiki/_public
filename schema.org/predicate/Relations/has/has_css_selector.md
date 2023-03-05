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
title: has_css_selector

linkTitle: has_css_selector
keywords: [css, selector]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- css-selector
- css_selector
- cssSelector
- has_css_selector
---

Use it like this: 
- [ #has/_css_selector :: CssSelectorType ] or 
- [ has_css_selector :: CssSelectorType ] 

A CSS selector, e.g. of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/SpeakableSpecification&quot;&gt;SpeakableSpecification&lt;/a&gt; or &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/WebPageElement&quot;&gt;WebPageElement&lt;/a&gt;. In the latter case, multiple matches within a page can constitute a single conceptual &quot;Web page element&quot;.

Relation describes that: 
[ #has_/domain  :: SpeakableSpecification, WebPageElement ]
( #has_/name :: is_css_selector )
( #has_/range :: CssSelectorType )

