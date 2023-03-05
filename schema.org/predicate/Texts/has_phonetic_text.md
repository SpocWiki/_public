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

title: has_text_about_phonetic_text
linkTitle: has_text_about_phonetic_text

keywords: [phonetic, text]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- phonetic-text
- phonetic_text
- phoneticText
- has_text_about_phonetic_text
---

Predicate to describe the Text of PronounceableText.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_phonetic_text :: Text ] or 
- [ has_text_about_phonetic_text :: Text ] 

Representation of a text &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/textValue&quot;&gt;textValue&lt;/a&gt; using the specified &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/speechToTextMarkup&quot;&gt;speechToTextMarkup&lt;/a&gt;. For example the city name of Houston in IPA: /?hju?st?n/.

Predicated describes that: 
[ #has_/domain  :: PronounceableText ]
( #has_/name :: is_phonetic_text )
( #has_/range :: Text )

