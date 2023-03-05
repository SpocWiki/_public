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
title: has_subtitle_language

linkTitle: has_subtitle_language
keywords: [subtitle, language]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- subtitle-language
- subtitle_language
- subtitleLanguage
- has_subtitle_language
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_subtitle_language :: Language, Text ] or 
- [ has_subtitle_language :: Language, Text ] 

Languages in which subtitles/captions are available, in &lt;a href&#x3D;&quot;http://tools.ietf.org/html/bcp47&quot;&gt;IETF BCP 47 standard format&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: BroadcastEvent, Movie, ScreeningEvent, TVEpisode ]
( #has_/name :: is_subtitle_language )
( #has_/range :: Language, Text )

