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

title: has_text_about_accessibility_summary
linkTitle: has_text_about_accessibility_summary

keywords: [accessibility, summary]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- accessibility-summary
- accessibility_summary
- accessibilitySummary
- has_text_about_accessibility_summary
---

Predicate to describe the Text of CreativeWork.

Use it like this: 
- [ #has_/text/_about_accessibility_summary :: Text ] or 
- [ has_text_about_accessibility_summary :: Text ] 

A human-readable summary of specific accessibility features or deficiencies, consistent with the other accessibility metadata but expressing subtleties such as &quot;short descriptions are present but long descriptions will be needed for non-visual users&quot; or &quot;short descriptions are present and no long descriptions are needed.&quot;

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: is_accessibility_summary )
( #has_/range :: Text )

