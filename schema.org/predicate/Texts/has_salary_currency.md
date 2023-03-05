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

title: has_text_about_salary_currency
linkTitle: has_text_about_salary_currency

keywords: [salary, currency]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- salary-currency
- salary_currency
- salaryCurrency
- has_text_about_salary_currency
---

Predicate to describe the Text of EmployeeRole, JobPosting.

Use it like this: 
- [ #has_/text/_about_salary_currency :: Text ] or 
- [ has_text_about_salary_currency :: Text ] 

The currency (coded using &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_4217&quot;&gt;ISO 4217&lt;/a&gt;) used for the main salary information in this job posting or for this employee.

Predicated describes that: 
[ #has_/domain  :: EmployeeRole, JobPosting ]
( #has_/name :: has_text_about_salary_currency )
( #has_/range :: Text )

