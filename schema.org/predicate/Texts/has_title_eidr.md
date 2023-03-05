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

title: has_text_about_title_eidr
linkTitle: has_text_about_title_eidr

keywords: [title, eidr]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- title-eidr
- title_eidr
- titleEIDR
- has_text_about_title_eidr
---

Predicate to describe the Text of Movie, TVEpisode.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_title_eidr :: Text, URL ] or 
- [ has_text_about_title_eidr :: Text, URL ] 

An &lt;a href&#x3D;&quot;https://eidr.org/&quot;&gt;EIDR&lt;/a&gt; (Entertainment Identifier Registry) &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/identifier&quot;&gt;identifier&lt;/a&gt; representing at the most general/abstract level, a work of film or television.&lt;br/&gt;&lt;br/&gt;

For example, the motion picture known as &quot;Ghostbusters&quot; has a titleEIDR of  &quot;10.5240/7EC7-228A-510A-053E-CBB8-J&quot;. This title (or work) may have several variants, which EIDR calls &quot;edits&quot;. See &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/editEIDR&quot;&gt;editEIDR&lt;/a&gt;.&lt;br/&gt;&lt;br/&gt;

Since schema.org types like &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Movie&quot;&gt;Movie&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/TVEpisode&quot;&gt;TVEpisode&lt;/a&gt; can be used for both works and their multiple expressions, it is possible to use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/titleEIDR&quot;&gt;titleEIDR&lt;/a&gt; alone (for a general description), or alongside &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/editEIDR&quot;&gt;editEIDR&lt;/a&gt; for a more edit-specific description.

Predicated describes that: 
[ #has_/domain  :: Movie, TVEpisode ]
( #has_/name :: has_text_about_title_eidr )
( #has_/range :: Text, URL )

[ #is_/sub_property_of  :: identifier ]

