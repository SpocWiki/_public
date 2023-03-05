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
title: has_publishing_principles

linkTitle: has_publishing_principles
keywords: [publishing, principles]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- publishing-principles
- publishing_principles
- publishingPrinciples
- has_publishing_principles
---

Use it like this: 
- [ #has/_publishing_principles :: CreativeWork, URL ] or 
- [ has_publishing_principles :: CreativeWork, URL ] 

The publishingPrinciples property indicates (typically via &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/URL&quot;&gt;URL&lt;/a&gt;) a document describing the editorial principles of an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Organization&quot;&gt;Organization&lt;/a&gt; (or individual, e.g. a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Person&quot;&gt;Person&lt;/a&gt; writing a blog) that relate to their activities as a publisher, e.g. ethics or diversity policies. When applied to a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CreativeWork&quot;&gt;CreativeWork&lt;/a&gt; (e.g. &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/NewsArticle&quot;&gt;NewsArticle&lt;/a&gt;) the principles are those of the party primarily responsible for the creation of the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CreativeWork&quot;&gt;CreativeWork&lt;/a&gt;.&lt;br/&gt;&lt;br/&gt;

While such policies are most typically expressed in natural language, sometimes related information (e.g. indicating a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/funder&quot;&gt;funder&lt;/a&gt;) can be expressed using schema.org terminology.

Relation describes that: 
[ #has_/domain  :: CreativeWork, Organization, Person ]
( #has_/name :: is_publishing_principles )
( #has_/range :: CreativeWork, URL )

[ #has_/sub_properties :: [ actionableFeedbackPolicy, correctionsPolicy, diversityStaffingReport, masthead, missionCoveragePrioritiesPolicy, noBylinesPolicy, ownershipFundingInfo, unnamedSourcesPolicy, verificationFactCheckingPolicy ] ]

