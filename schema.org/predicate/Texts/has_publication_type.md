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

title: has_text_about_publication_type
linkTitle: has_text_about_publication_type

keywords: [publication, type]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- publication-type
- publication_type
- publicationType
- has_text_about_publication_type
---

Predicate to describe the Text of MedicalScholarlyArticle.

Use it like this: 
- [ #has_/text/_about_publication_type :: Text ] or 
- [ has_text_about_publication_type :: Text ] 

The type of the medical article, taken from the US NLM MeSH publication type catalog. See also &lt;a href&#x3D;&quot;http://www.nlm.nih.gov/mesh/pubtypes.html&quot;&gt;MeSH documentation&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: MedicalScholarlyArticle ]
( #has_/name :: has_text_about_publication_type )
( #has_/range :: Text )

