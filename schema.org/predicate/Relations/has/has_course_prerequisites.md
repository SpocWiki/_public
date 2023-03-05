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
keywords: 
layout: 
draft: false
publishDate:
expiryDate: 

supersedes: 
superseded_by: 

tags:
- schema.org/Predicate/Relation

aliases:
- course-prerequisites
- course_prerequisites
- coursePrerequisites
- has_course_prerequisites
---

Use it like this: 
- [ #has/_course_prerequisites :: AlignmentObject, Course, Text] or 
- [ has_course_prerequisites :: AlignmentObject, Course, Text] 

Requirements for taking the Course. May be completion of another &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Course&quot;&gt;Course&lt;/a&gt; or a textual description like &quot;permission of instructor&quot;. Requirements may be a pre-requisite competency, referenced using &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/AlignmentObject&quot;&gt;AlignmentObject&lt;/a&gt;.

Relation describes that: 
[ #has_/domain  :: Course]
( #has_/name :: is_course_prerequisites)
( #has_/range :: AlignmentObject, Course, Text)

