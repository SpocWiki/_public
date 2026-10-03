---
title: Untitled
linkTitle: 
keywords: 
layout: 
draft: false
expiryDate: 
type: 
has_time_created: 
has_time_destroyed: 
has_location_created: 
has_location_destroyed: 
has_creator:
- []
has_destroyer:
- []
isDeleted: false
isReadOnly: false
confidential: private
Key: Value
Predicate:
- - Object
cssclasses: 
publish: false
aliases:
- 
tags:
- "rather use"
lang: en
---
SpocWiki is the Name of the Markdown GIT Organization and Project to collect public data in an open Format. 

It also involves Media (Graphics, Music, Photos etc.) which should [preferably be copied](https://commons.wikimedia.org/wiki/Commons:Reusing_content_outside_Wikimedia/technical) from open sources. 
[Hotlinking](https://en.wikipedia.org/wiki/Inline_linking "w:Inline linking") is _allowed_ from Wikimedia servers, but _not generally recommended_: this is because anyone could change, vandalise, [rename](https://phabricator.wikimedia.org/T37721 "phab:T37721") or delete a hotlinked image. On your own server, you will have control over what is served.
If you _do_ hotlink, then it is still necessary to follow the licensing conditions. 


## Confidential Links & Embeds: 
- [[/_Standards/SpocWiki|SpocWiki]] 
- [[../_public/SpocWiki.public|SpocWiki.public]] 
- [[../_internal/SpocWiki.internal|SpocWiki.internal]] 
- [[../_protect/SpocWiki.protect|SpocWiki.protect]] 
- [[../_private/SpocWiki.private|SpocWiki.private]] 
- [[../_personal/SpocWiki.personal|SpocWiki.personal]] 
- [[../_secret/SpocWiki.secret|SpocWiki.secret]]


## Merged from `_0-New/SpocWiki.md`

Checklist for starting a Project:
[Starting an Open Source Project | Open Source Guides](https://opensource.guide/starting-a-project/)

Tags: #IT #URL
Links: rather use typed Links using [key::link] or (key::link)

MetaData: like Created, modified etc. can be extracted from FileVersioning in OS or GIT, not within the same File.

Also use [Hugo Metadata Front Matter](https://gohugo.io/content-management/front-matter/) to control Publishing
Use [Schema.org - Schemas](https://schema.org/docs/schemas.html) to add MetaData and Facts.

# Ideas
* describe the key Ideas in single Sentences and make Headings and a ToC from them

# 'Outside' File Name Structure is best!
Similar to the File Name being an Abstract of the Contents.
Links are simple preserved when Folder is introduced.
Moving / zipping Folder loses Details but that may be an advantage.
* Move file and Folder of same Name together!

## Folder Notes
3 Methods are discussed: [obsidian-folder-note-plugin/folder-note-methods.md at main · xpgo/obsidian-folder-note-plugin (github.com)](https://github.com/xpgo/obsidian-folder-note-plugin/blob/main/doc/folder-note-methods)
* Index File similar to index.htm or default.htm or .md (not allowed)
* Outside File Name (not moved together)
* Inside File Name (lost within other Files)

# Examples
*

# Links
* Internal [ [WikiLinks]] are handled only by Obsidian or other Wiki Software and abstract from the Path
* Alternatively, any CamelCase (used in TiddlyWiki and Ward Cunninghams Wiki) /relative/Path or Text_with_Underscore may be recognized as a nerdy WikiLink that has to be humanized and converted to a relative Path.
* Other [MarkDown](https://www.markdownguide.org/cheat-sheet/) Apps require proper [ markdown] (Links with relative or absolute Path)
*

# Media
- Media can become large, so it exceeds free Cloud offerings
	- either put it into a single xLarge Folder in an outer Vault and sync only the inner Vault
	- or create a Folder as soon as you have Attachments and ignore it in .gitIgnore
		- could also use File Attributes for that
	- adding a .nosync Extension (anywhere) to every File works, but is not practical!
	- Limitations of Git Working Copy:
		- no push commits
		- less than 5 repositories.
	- - adding a .nosync Extension (anywhere) to every File works, but is not practical!
	- Limitations of Git Working Copy:
		- no push commits
		- less than 5 repositories.
	-
