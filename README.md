# ifttt e canale telegram
---

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/if.png"></p>


# New feed item

## Feed URL

https://feedpress.me/gds_hp_palermo (url del feed RSS)

↓

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/then.png"></p>


# Make a web request

### URL:

https://api.telegram.org/bot256932411:AAFi0hEeve79ujB3i84ZkUYkJIVtBtTTFoE/sendMessage

### Method

POST

### Content Type

application/x-www-form-urlencoded


### Body
chat_id=@AnsaSicilia&text= {{EntryTitle}} {{EntryUrl}}

(Surround any text with <<< and >>> to escape the content)


