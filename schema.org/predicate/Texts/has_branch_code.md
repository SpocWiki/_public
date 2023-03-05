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

title: has_text_about_branch_code
linkTitle: has_text_about_branch_code

keywords: [branch, code]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- branch-code
- branch_code
- branchCode
- has_text_about_branch_code
---

Predicate to describe the Text of Place.

Use it like this: 
- [ #has_/text/_about_branch_code :: Text ] or 
- [ has_text_about_branch_code :: Text ] 

A short textual code (also called &quot;store code&quot;) that uniquely identifies a place of business. The code is typically assigned by the parentOrganization and used in structured URLs.&lt;br/&gt;&lt;br/&gt;

For example, in the URL http://www.starbucks.co.uk/store-locator/etc/detail/3047 the code &quot;3047&quot; is a branchCode for a particular branch.

Predicated describes that: 
[ #has_/domain  :: Place ]
( #has_/name :: has_text_about_branch_code )
( #has_/range :: Text )

