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
title: has_occupational_credential_awarded

linkTitle: has_occupational_credential_awarded
keywords: [occupational, credential, awarded]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- occupational-credential-awarded
- occupational_credential_awarded
- occupationalCredentialAwarded
- has_occupational_credential_awarded
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_occupational_credential_awarded :: EducationalOccupationalCredential, Text, URL ] or 
- [ has_occupational_credential_awarded :: EducationalOccupationalCredential, Text, URL ] 

A description of the qualification, award, certificate, diploma or other occupational credential awarded as a consequence of successful completion of this course or program.

Relation describes that: 
[ #has_/domain  :: Course, EducationalOccupationalProgram ]
( #has_/name :: has_occupational_credential_awarded )
( #has_/range :: EducationalOccupationalCredential, Text, URL )

