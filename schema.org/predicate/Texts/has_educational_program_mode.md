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

title: has_text_about_educational_program_mode
linkTitle: has_text_about_educational_program_mode

keywords: [educational, program, mode]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- educational-program-mode
- educational_program_mode
- educationalProgramMode
- has_text_about_educational_program_mode
---

Predicate to describe the Text of EducationalOccupationalProgram.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_educational_program_mode :: Text, URL ] or 
- [ has_text_about_educational_program_mode :: Text, URL ] 

Similar to courseMode, the medium or means of delivery of the program as a whole. The value may either be a text label (e.g. &quot;online&quot;, &quot;onsite&quot; or &quot;blended&quot;; &quot;synchronous&quot; or &quot;asynchronous&quot;; &quot;full-time&quot; or &quot;part-time&quot;) or a URL reference to a term from a controlled vocabulary (e.g. https://ceds.ed.gov/element/001311#Asynchronous ).

Predicated describes that: 
[ #has_/domain  :: EducationalOccupationalProgram ]
( #has_/name :: has_text_about_educational_program_mode )
( #has_/range :: Text, URL )

