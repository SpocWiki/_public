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

title: has_text_about_report_number
linkTitle: has_text_about_report_number

keywords: [report, number]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- report-number
- report_number
- reportNumber
- has_text_about_report_number
---

Predicate to describe the Text of Report.

Use it like this: 
- [ #has_/text/_about_report_number :: Text ] or 
- [ has_text_about_report_number :: Text ] 

The number or other unique designator assigned to a Report by the publishing organization.

Predicated describes that: 
[ #has_/domain  :: Report ]
( #has_/name :: has_text_about_report_number )
( #has_/range :: Text )

