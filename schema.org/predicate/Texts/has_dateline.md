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

title: has_text_about_dateline
linkTitle: has_text_about_dateline

keywords: [dateline]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- dateline
- dateline
- dateline
- has_text_about_dateline
---

Predicate to describe the Text of NewsArticle.

Use it like this: 
- [ #has_/text/_about_dateline :: Text ] or 
- [ has_text_about_dateline :: Text ] 

A &lt;a href="https://en.wikipedia.org/wiki/Dateline"&gt;dateline&lt;/a&gt; is a brief piece of text included in news articles that describes where and when the story was written or filed though the date is often omitted. Sometimes only a placename is provided.&lt;br/&gt;&lt;br/&gt;

Structured representations of dateline-related information can also be expressed more explicitly using &lt;a class="localLink" href="/locationCreated"&gt;locationCreated&lt;/a&gt; (which represents where a work was created, e.g. where a news report was written).  For location depicted or described in the content, use &lt;a class="localLink" href="/contentLocation"&gt;contentLocation&lt;/a&gt;.&lt;br/&gt;&lt;br/&gt;

Dateline summaries are oriented more towards human readers than towards automated processing, and can vary substantially. Some examples: "BEIRUT, Lebanon, June 2.", "Paris, France", "December 19, 2017 11:43AM Reporting from Washington", "Beijing/Moscow", "QUEZON CITY, Philippines".

Predicated describes that: 
[ #has_/domain  :: NewsArticle ]
( #has_/name :: has_text_about_dateline )
( #has_/range :: Text )

