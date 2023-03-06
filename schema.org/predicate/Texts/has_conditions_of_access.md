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

title: has_text_about_conditions_of_access
linkTitle: has_text_about_conditions_of_access

keywords: [conditions, of, access]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- conditions-of-access
- conditions_of_access
- conditionsOfAccess
- has_text_about_conditions_of_access
---

Predicate to describe the Text of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_conditions_of_access :: Text ] or 
- [ has_text_about_conditions_of_access :: Text ] 

Conditions that affect the availability of, or method(s) of access to, an item. Typically used for real world items such as an &lt;a class="localLink" href="/ArchiveComponent"&gt;ArchiveComponent&lt;/a&gt; held by an &lt;a class="localLink" href="/ArchiveOrganization"&gt;ArchiveOrganization&lt;/a&gt;. This property is not suitable for use as a general Web access control mechanism. It is expressed only in natural language.&lt;br/&gt;&lt;br/&gt;

For example "Available by appointment from the Reading Room" or "Accessible only from logged-in accounts ".

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_text_about_conditions_of_access )
( #has_/range :: Text )

