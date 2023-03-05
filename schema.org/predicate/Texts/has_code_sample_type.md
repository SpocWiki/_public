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

title: has_text_about_code_sample_type
linkTitle: has_text_about_code_sample_type

keywords: [code, sample, type]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: sampleType

tags:
- schema.org/Predicate/Text

aliases:
- code-sample-type
- code_sample_type
- codeSampleType
- has_text_about_code_sample_type
---

Predicate to describe the Text of SoftwareSourceCode.

Use it like this: 
- [ #has_/text/_about_code_sample_type :: Text ] or 
- [ has_text_about_code_sample_type :: Text ] 

What type of code sample: full (compile ready) solution, code snippet, inline code, scripts, template.

Predicated describes that: 
[ #has_/domain  :: SoftwareSourceCode ]
( #has_/name :: is_code_sample_type )
( #has_/range :: Text )

