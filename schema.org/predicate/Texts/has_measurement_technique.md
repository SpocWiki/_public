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

title: has_text_about_measurement_technique
linkTitle: has_text_about_measurement_technique

keywords: [measurement, technique]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- measurement-technique
- measurement_technique
- measurementTechnique
- has_text_about_measurement_technique
---

Predicate to describe the Text of DataCatalog, DataDownload, Dataset, PropertyValue.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_measurement_technique :: Text, URL ] or 
- [ has_text_about_measurement_technique :: Text, URL ] 

A technique or technology used in a &lt;a class="localLink" href="/Dataset"&gt;Dataset&lt;/a&gt; (or &lt;a class="localLink" href="/DataDownload"&gt;DataDownload&lt;/a&gt;, &lt;a class="localLink" href="/DataCatalog"&gt;DataCatalog&lt;/a&gt;),
corresponding to the method used for measuring the corresponding variable(s) (described using &lt;a class="localLink" href="/variableMeasured"&gt;variableMeasured&lt;/a&gt;). This is oriented towards scientific and scholarly dataset publication but may have broader applicability; it is not intended as a full representation of measurement, but rather as a high level summary for dataset discovery.&lt;br/&gt;&lt;br/&gt;

For example, if &lt;a class="localLink" href="/variableMeasured"&gt;variableMeasured&lt;/a&gt; is: molecule concentration, &lt;a class="localLink" href="/measurementTechnique"&gt;measurementTechnique&lt;/a&gt; could be: "mass spectrometry" or "nmr spectroscopy" or "colorimetry" or "immunofluorescence".&lt;br/&gt;&lt;br/&gt;

If the &lt;a class="localLink" href="/variableMeasured"&gt;variableMeasured&lt;/a&gt; is "depression rating", the &lt;a class="localLink" href="/measurementTechnique"&gt;measurementTechnique&lt;/a&gt; could be "Zung Scale" or "HAM-D" or "Beck Depression Inventory".&lt;br/&gt;&lt;br/&gt;

If there are several &lt;a class="localLink" href="/variableMeasured"&gt;variableMeasured&lt;/a&gt; properties recorded for some given data object, use a &lt;a class="localLink" href="/PropertyValue"&gt;PropertyValue&lt;/a&gt; for each &lt;a class="localLink" href="/variableMeasured"&gt;variableMeasured&lt;/a&gt; and attach the corresponding &lt;a class="localLink" href="/measurementTechnique"&gt;measurementTechnique&lt;/a&gt;.

Predicated describes that: 
[ #has_/domain  :: DataCatalog, DataDownload, Dataset, PropertyValue ]
( #has_/name :: has_text_about_measurement_technique )
( #has_/range :: Text, URL )

