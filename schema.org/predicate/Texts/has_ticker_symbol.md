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

title: has_text_about_ticker_symbol
linkTitle: has_text_about_ticker_symbol

keywords: [ticker, symbol]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- ticker-symbol
- ticker_symbol
- tickerSymbol
- has_text_about_ticker_symbol
---

Predicate to describe the Text of Corporation.

Use it like this: 
- [ #has_/text/_about_ticker_symbol :: Text ] or 
- [ has_text_about_ticker_symbol :: Text ] 

The exchange traded instrument associated with a Corporation object. The tickerSymbol is expressed as an exchange and an instrument name separated by a space character. For the exchange component of the tickerSymbol attribute, we recommend using the controlled vocabulary of Market Identifier Codes (MIC) specified in ISO 15022.

Predicated describes that: 
[ #has_/domain  :: Corporation ]
( #has_/name :: is_ticker_symbol )
( #has_/range :: Text )

