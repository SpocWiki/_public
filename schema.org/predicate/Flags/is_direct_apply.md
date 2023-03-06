---
license: CC BY-SA 4.0
confidential: public
isDeleted: false
isReadOnly: false

#Obsidian well-known Keys
cssclass: Predicate Boolean
publish: true

# Hugo Tags
type: Pred_Bool

title: is_direct_apply
linkTitle: is_direct_apply

keywords: [direct_apply]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/True

aliases:
- direct-apply
- direct_apply
- directApply
- is_direct_apply
---

[ #is_/part_of :: pending: ]

Use these simple Tags to mark Instances as True or False: 
#is_/_/direct_apply 
#is_/not/direct_apply 

Or write it as a Triple: 
[ is_direct_apply :: Boolean ] 

Indicates whether an &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/url&quot;&gt;url&lt;/a&gt; that is associated with a &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/JobPosting&quot;&gt;JobPosting&lt;/a&gt; enables direct application for the job, via the posting website. A job posting is considered to have directApply of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/True&quot;&gt;True&lt;/a&gt; if an application process for the specified job can be directly initiated via the url(s) given (noting that e.g. multiple internet domains might nevertheless be involved at an implementation level). A value of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/False&quot;&gt;False&lt;/a&gt; is appropriate if there is no clear path to applying directly online for the specified job, navigating directly from the JobPosting url(s) supplied.

Predicate describes that: 
[ #has_/domain  :: JobPosting ]
( #has_/name :: is_direct_apply )
( #has_/range :: Boolean )

