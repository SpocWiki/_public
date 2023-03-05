---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Text
publish: true

# Hugo Tags
type: Pred_Text

title: has_text_about_encoding_format
linkTitle: has_text_about_encoding_format

keywords: [encoding, format]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: fileFormat

tags:
- schema.org/Predicate/Text

aliases:
- encoding-format
- encoding_format
- encodingFormat
- has_text_about_encoding_format
---

Predicate to describe the Text of CreativeWork, MediaObject.

Use it like this: 
- [ #has_/text/_about_encoding_format :: Text, URL ] or 
- [ has_text_about_encoding_format :: Text, URL ] 

Media type typically expressed using a MIME format (see &lt;a href&#x3D;&quot;http://www.iana.org/assignments/media-types/media-types.xhtml&quot;&gt;IANA site&lt;/a&gt; and &lt;a href&#x3D;&quot;https://developer.mozilla.org/en-US/docs/Web/HTTP/Basics_of_HTTP/MIME_types&quot;&gt;MDN reference&lt;/a&gt;), e.g. application/zip for a SoftwareApplication binary, audio/mpeg for .mp3 etc.&lt;br/&gt;&lt;br/&gt;

In cases where a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/CreativeWork&quot;&gt;CreativeWork&lt;/a&gt; has several media type representations, &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/encoding&quot;&gt;encoding&lt;/a&gt; can be used to indicate each &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/MediaObject&quot;&gt;MediaObject&lt;/a&gt; alongside particular &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/encodingFormat&quot;&gt;encodingFormat&lt;/a&gt; information.&lt;br/&gt;&lt;br/&gt;

Unregistered or niche encoding and file formats can be indicated instead via the most appropriate URL, e.g. defining Web page or a Wikipedia/Wikidata entry.

Predicated describes that: 
[ #has_/domain  :: CreativeWork, MediaObject ]
( #has_/name :: has_text_about_encoding_format )
( #has_/range :: Text, URL )

