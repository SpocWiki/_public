---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Url
publish: true

# Hugo Tags
type: Predi_Url

title: has_url_for_archived_at
linkTitle: has_url_for_archived_at

keywords: [archived_at]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Url

aliases:
- archived-at
- archived_at
- archivedAt
- has_url_for_archived_at
---

Predicate to specify the Url of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/url/_for_archived_at :: URL, WebPage ] or 
- [ has_url_for_archived_at :: URL, WebPage ] 

Indicates a page or other link involved in archival of a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CreativeWork&quot;&gt;CreativeWork&lt;/a&gt;. In the case of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MediaReview&quot;&gt;MediaReview&lt;/a&gt;, the items in a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MediaReviewItem&quot;&gt;MediaReviewItem&lt;/a&gt; may often become inaccessible, but be archived by archival, journalistic, activist, or law enforcement organizations. In such cases, the referenced page may not directly publish the content.

Predicate describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_url_for_archived_at )
( #has_/range :: URL, WebPage )

