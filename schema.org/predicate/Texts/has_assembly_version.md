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

title: has_text_about_assembly_version
linkTitle: has_text_about_assembly_version

keywords: [assembly, version]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- assembly-version
- assembly_version
- assemblyVersion
- has_text_about_assembly_version
---

Predicate to describe the Text of APIReference.

Use it like this: 
- [ #has_/text/_about_assembly_version :: Text ] or 
- [ has_text_about_assembly_version :: Text ] 

Associated product/technology version. E.g., .NET Framework 4.5.

Predicated describes that: 
[ #has_/domain  :: APIReference ]
( #has_/name :: is_assembly_version )
( #has_/range :: Text )

