# ifttt e canale telegram per i feed RSS
agganciare un feed RSS ad un canale Telegram grazie al servizio web di IFTTT

## Edit Applet

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/if.png"></p>

# New feed item

## Feed URL

https://feedpress.me/gds_hp_palermo (url del feed RSS)

↓

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/then.png"></p>


# Make a web request

### URL:

<code>https://api.telegram.org/bot256932411:AAFi0hEeve79ujB3i84ZkUYkJIVtBtTTFoE/sendMessage</code>

### Method

<code>POST</code>

### Content Type

<code>application/x-www-form-urlencoded</code>


### Body
<code>chat_id=@AnsaSicilia&text= {{EntryTitle}} {{EntryUrl}}</code>

Surround any text with <<< and >>> to escape the content


