# Predicate Overview

Predicates are the Union of Property- and Relation-Types. 
The Document is always the (implied) Subject of a Relation or Property/Quantity. 

* Relations: another Document/Object is referenced. 
* Property/Quantity: a Value is given. This can be a string, but also JSON Types like double, int, DateTime etc. Depending on the Value Type we distinguish 
	* Strings: Labels, Names, Descriptions etc. 
	* Counts: 
	* Quantities: 1-dimensional Scalars but also 2D and 3D Vectors for Locations 
	* Tags: Tags are Boolean Properties and have a simplified Syntax using # 
	* Time: 

Predicate Names typically...
- start with `is-` e.g. for passive Relations or...
- start with `has-` or end with `-is` for Properties 

Type Names start with 'Type-'  `Type-` to indicate this
Alternatively, Types could be indicated by the Plural Form, 
but that is too close to the Name of arbitrary Collections. 

By generating Folders with dedicated Templates for each Type 
you can promote consistent Naming. 