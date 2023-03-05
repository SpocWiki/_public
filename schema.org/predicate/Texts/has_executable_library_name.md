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

title: has_text_about_executable_library_name
linkTitle: has_text_about_executable_library_name

keywords: [executable, library, name]
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: assembly

tags:
- schema.org/Predicate/Text

aliases:
- executable-library-name
- executable_library_name
- executableLibraryName
- has_text_about_executable_library_name
---

Predicate to describe the Text of APIReference.

Use it like this: 
- [ #has_/text/_about_executable_library_name :: Text ] or 
- [ has_text_about_executable_library_name :: Text ] 

Library file name, e.g., mscorlib.dll, system.web.dll.

Predicated describes that: 
[ #has_/domain  :: APIReference ]
( #has_/name :: has_text_about_executable_library_name )
( #has_/range :: Text )

