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

title: has_text_about_currencies_accepted
linkTitle: has_text_about_currencies_accepted

keywords: [currencies, accepted]
layout: 
draft: false
publishDate:
expiryDate: 

tags:
- schema.org/Predicate/Text

aliases:
- currencies-accepted
- currencies_accepted
- currenciesAccepted
- has_text_about_currencies_accepted
---

Predicate to describe the Text of LocalBusiness.

Use it like this: 
- [ #has_/text/_about_currencies_accepted :: Text ] or 
- [ has_text_about_currencies_accepted :: Text ] 

The currency accepted.&lt;br/&gt;&lt;br/&gt;

Use standard formats: &lt;a href&#x3D;&quot;http://en.wikipedia.org/wiki/ISO_4217&quot;&gt;ISO 4217 currency format&lt;/a&gt;, e.g. &quot;USD&quot;; &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/List_of_cryptocurrencies&quot;&gt;Ticker symbol&lt;/a&gt; for cryptocurrencies, e.g. &quot;BTC&quot;; well known names for &lt;a href&#x3D;&quot;https://en.wikipedia.org/wiki/Local_exchange_trading_system&quot;&gt;Local Exchange Trading Systems&lt;/a&gt; (LETS) and other currency types, e.g. &quot;Ithaca HOUR&quot;.

Predicated describes that: 
[ #has_/domain  :: LocalBusiness ]
( #has_/name :: is_currencies_accepted )
( #has_/range :: Text )

