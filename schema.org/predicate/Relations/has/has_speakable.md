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
title: has_speakable

linkTitle: has_speakable
keywords: [speakable]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- speakable
- speakable
- speakable
- has_speakable
---

Use it like this: 
- [ #has/_speakable :: SpeakableSpecification, URL ] or 
- [ has_speakable :: SpeakableSpecification, URL ] 

Indicates sections of a Web page that are particularly &#x27;speakable&#x27; in the sense of being highlighted as being especially appropriate for text-to-speech conversion. Other sections of a page may also be usefully spoken in particular circumstances; the &#x27;speakable&#x27; property serves to indicate the parts most likely to be generally useful for speech.&lt;br/&gt;&lt;br/&gt;

The &lt;em&gt;speakable&lt;/em&gt; property can be repeated an arbitrary number of times, with three kinds of possible &#x27;content-locator&#x27; values:&lt;br/&gt;&lt;br/&gt;

1.) &lt;em&gt;id-value&lt;/em&gt; URL references - uses &lt;em&gt;id-value&lt;/em&gt; of an element in the page being annotated. The simplest use of &lt;em&gt;speakable&lt;/em&gt; has (potentially relative) URL values, referencing identified sections of the document concerned.&lt;br/&gt;&lt;br/&gt;

2.) CSS Selectors - addresses content in the annotated page, e.g. via class attribute. Use the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/cssSelector&quot;&gt;cssSelector&lt;/a&gt; property.&lt;br/&gt;&lt;br/&gt;

3.)  XPaths - addresses content via XPaths (assuming an XML view of the content). Use the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/xpath&quot;&gt;xpath&lt;/a&gt; property.&lt;br/&gt;&lt;br/&gt;

For more sophisticated markup of speakable sections beyond simple ID references, either CSS selectors or XPath expressions to pick out document section(s) as speakable. For this
we define a supporting type, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/SpeakableSpecification&quot;&gt;SpeakableSpecification&lt;/a&gt;  which is defined to be a possible value of the &lt;em&gt;speakable&lt;/em&gt; property.

Relation describes that: 
[ #has_/domain  :: Article, WebPage ]
( #has_/name :: is_speakable )
( #has_/range :: SpeakableSpecification, URL )

