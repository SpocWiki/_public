---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Relation
publish: true

# Hugo Tags
type: Predi_Relation
title: has_course_prerequisites

linkTitle: has_course_prerequisites
keywords: [course, prerequisites]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- course-prerequisites
- course_prerequisites
- coursePrerequisites
- has_course_prerequisites
---

Use it like this: 
- [ #has/_course_prerequisites :: AlignmentObject, Course, Text ] or 
- [ has_course_prerequisites :: AlignmentObject, Course, Text ] 

Requirements for taking the Course. May be completion of another &lt;a class="localLink" href="/Course"&gt;Course&lt;/a&gt; or a textual description like "permission of instructor". Requirements may be a pre-requisite competency, referenced using &lt;a class="localLink" href="/AlignmentObject"&gt;AlignmentObject&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Course ]
( #has_/name :: has_course_prerequisites )
( #has_/range :: AlignmentObject, Course, Text )

