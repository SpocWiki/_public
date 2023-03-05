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

title: has_text_about_edit_eidr
linkTitle: has_text_about_edit_eidr

keywords: [edit, eidr]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- edit-eidr
- edit_eidr
- editEIDR
- has_text_about_edit_eidr
---

Predicate to describe the Text of CreativeWork.

[ #is_/part_of :: pending: ]

Use it like this: 
- [ #has_/text/_about_edit_eidr :: Text, URL ] or 
- [ has_text_about_edit_eidr :: Text, URL ] 

An &lt;a href&#x3D;&quot;https://eidr.org/&quot;&gt;EIDR&lt;/a&gt; (Entertainment Identifier Registry) &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/identifier&quot;&gt;identifier&lt;/a&gt; representing a specific edit / edition for a work of film or television.&lt;br/&gt;&lt;br/&gt;

For example, the motion picture known as &quot;Ghostbusters&quot; whose &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/titleEIDR&quot;&gt;titleEIDR&lt;/a&gt; is &quot;10.5240/7EC7-228A-510A-053E-CBB8-J&quot; has several edits, e.g. &quot;10.5240/1F2A-E1C5-680A-14C6-E76B-I&quot; and &quot;10.5240/8A35-3BEE-6497-5D12-9E4F-3&quot;.&lt;br/&gt;&lt;br/&gt;

Since schema.org types like &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/Movie&quot;&gt;Movie&lt;/a&gt; and &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/TVEpisode&quot;&gt;TVEpisode&lt;/a&gt; can be used for both works and their multiple expressions, it is possible to use &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/titleEIDR&quot;&gt;titleEIDR&lt;/a&gt; alone (for a general description), or alongside &lt;a class&#x3D;&quot;localLink&quot; href&#x3D;&quot;/editEIDR&quot;&gt;editEIDR&lt;/a&gt; for a more edit-specific description.

Predicated describes that: 
[ #has_/domain  :: CreativeWork ]
( #has_/name :: has_text_about_edit_eidr )
( #has_/range :: Text, URL )

[ #is_/sub_property_of  :: identifier ]

