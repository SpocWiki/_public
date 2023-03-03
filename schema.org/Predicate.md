
# Predicate Overview

Predicates are the Union of Tags, Property- and Relation-Types. 
Predicates are the inner Object of an S-P-O Triple/Claim 
The Document is always the (implied) Subject of a Relation or Property/Quantity. 

* Relations: another Document/Object is referenced. Schema.org defines ca. 700 Relations 
	* TODO: ==Quantities with Enumerations as Values need to be decided on!==
* Property/Quantity: a Value is given. This can be a string, but also JSON Types like double, int, DateTime etc. Depending on the Value Type we distinguish 
	* Strings: Labels, Names, URLs, Descriptions etc. 
	* Counts: 
	* Quantities: 1-dimensional Scalars but also 2D and 3D Vectors for Locations 
	* Tags: Tags are Boolean Properties and have a simplified Syntax using # denoting a Class or Set Relation
	* Time: 

Predicate Names typically...
- start with `is-` or `are` e.g. for passive Relations or...
- start with `has-`, `have`, `does` or end with `-is` (for Type Statement )

Type Names start with 'Type-'  `Type-` to indicate this
Alternatively, Types could be indicated by the Plural Form, 
but that is too close to the Name of arbitrary Collections. 

By generating Folders with dedicated Templates for each Type 
you can promote consistent Naming. 

Derived from [Schema.org](https://schema.org/docs/developers.html) 
