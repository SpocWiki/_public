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
title: has_return_policy_country

linkTitle: has_return_policy_country
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
- return-policy-country
- return_policy_country
- returnPolicyCountry
- has_return_policy_country
---

[ #is_/part_of :: pending:]

Use it like this: 
- [ #has/_return_policy_country :: Country, Text] or 
- [ has_return_policy_country :: Country, Text] 

The country where the product has to be sent to for returns, for example &quot;Ireland&quot; using the &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/name&quot;&gt;name&lt;/a&gt; property of &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Country&quot;&gt;Country&lt;/a&gt;. You can also provide the two-letter &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_3166-1&quot;&gt;ISO 3166-1 alpha-2 country code&lt;/a&gt;. Note that this can be different from the country where the product was originally shipped from or sent to.

Relation describes that: 
[ #has_/domain  :: MerchantReturnPolicy]
( #has_/name :: is_return_policy_country)
( #has_/range :: Country, Text)

