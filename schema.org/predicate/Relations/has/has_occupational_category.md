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
title: has_occupational_category

linkTitle: has_occupational_category
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
- occupational-category
- occupational_category
- occupationalCategory
- has_occupational_category
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_occupational_category :: CategoryCode, Text] or 
- [ has_occupational_category :: CategoryCode, Text] 

A category describing the job, preferably using a term from a taxonomy such as &lt;a href&#x3D;&quot;http://www.onetcenter.org/taxonomy.html&quot;&gt;BLS O*NET-SOC&lt;/a&gt;, &lt;a href&#x3D;&quot;https://www.ilo.org/public/english/bureau/stat/isco/isco08/&quot;&gt;ISCO-08&lt;/a&gt; or similar, with the property repeated for each applicable value. Ideally the taxonomy should be identified, and both the textual label and formal code for the category should be provided.&lt;br/&gt;&lt;br/&gt;

Note: for historical reasons, any textual label and formal code provided as a literal may be assumed to be from O*NET-SOC.

Relation describes that: 
[ #has_/domain  :: EducationalOccupationalProgram, JobPosting, Occupation, WorkBasedProgram]
( #has_/name :: is_occupational_category)
( #has_/range :: CategoryCode, Text)

[ #is_/inverse_of  :: ]

[ #is_/sub_property_of  :: ]

[ #has_/sub_properties :: ]
