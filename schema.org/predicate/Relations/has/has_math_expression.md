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
title: has_math_expression

linkTitle: has_math_expression
keywords: [math, expression]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Relation

aliases:
- math-expression
- math_expression
- mathExpression
- has_math_expression
---

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has/_math_expression :: SolveMathAction, Text ] or 
- [ has_math_expression :: SolveMathAction, Text ] 

A mathematical expression (e.g. 'x^2-3x=0') that may be solved for a specific variable, simplified, or transformed. This can take many formats, e.g. LaTeX, Ascii-Math, or math as you would write with a keyboard.

Relation describes that: 
[ #has_/domain  :: MathSolver ]
( #has_/name :: is_math_expression )
( #has_/range :: SolveMathAction, Text )

