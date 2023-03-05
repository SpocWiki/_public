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

title: has_text_about_ticket_token
linkTitle: has_text_about_ticket_token

keywords: [ticket, token]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- ticket-token
- ticket_token
- ticketToken
- has_text_about_ticket_token
---

Predicate to describe the Text of Ticket.

Use it like this: 
- [ #has_/text/_about_ticket_token :: Text, URL ] or 
- [ has_text_about_ticket_token :: Text, URL ] 

Reference to an asset (e.g., Barcode, QR code image or PDF) usable for entrance.

Predicated describes that: 
[ #has_/domain  :: Ticket ]
( #has_/name :: is_ticket_token )
( #has_/range :: Text, URL )

