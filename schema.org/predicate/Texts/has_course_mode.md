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

title: has_text_about_course_mode
linkTitle: has_text_about_course_mode

keywords: [course, mode]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- course-mode
- course_mode
- courseMode
- has_text_about_course_mode
---

Predicate to describe the Text of CourseInstance.

Use it like this: 
- [ #has_/text/_about_course_mode :: Text, URL ] or 
- [ has_text_about_course_mode :: Text, URL ] 

The medium or means of delivery of the course instance or the mode of study, either as a text label (e.g. "online", "onsite" or "blended"; "synchronous" or "asynchronous"; "full-time" or "part-time") or as a URL reference to a term from a controlled vocabulary (e.g. https://ceds.ed.gov/element/001311#Asynchronous).

Predicated describes that: 
[ #has_/domain  :: CourseInstance ]
( #has_/name :: has_text_about_course_mode )
( #has_/range :: Text, URL )

