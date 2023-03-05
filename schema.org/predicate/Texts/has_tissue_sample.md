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

title: has_text_about_tissue_sample
linkTitle: has_text_about_tissue_sample

keywords: [tissue, sample]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- tissue-sample
- tissue_sample
- tissueSample
- has_text_about_tissue_sample
---

Predicate to describe the Text of PathologyTest.

Use it like this: 
- [ #has_/text/_about_tissue_sample :: Text ] or 
- [ has_text_about_tissue_sample :: Text ] 

The type of tissue sample required for the test.

Predicated describes that: 
[ #has_/domain  :: PathologyTest ]
( #has_/name :: has_text_about_tissue_sample )
( #has_/range :: Text )

