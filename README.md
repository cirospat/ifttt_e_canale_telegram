[IFTTT](https://ifttt.com/home) per creare canale [Telegram](https://desktop.telegram.org/) con i feed [RSS](https://it.wikipedia.org/wiki/RSS)
=======
agganciare un feed RSS ad un canale Telegram grazie al servizio web di IFTTT

## Edit Applet

[**create**](https://ifttt.com/create) 

cerca <code>RSS</code>

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/if.png"></p>

# New feed item

## Feed URL

inerisci il link del feed RSS https://feedpress.me/gds_hp_palermo (url del feed RSS)

↓

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/then.png"></p>


# Make a web request

### URL:

digita il link dell'API che ti fornisce il BOT  che hai creato grazie a Bot father su Telegram (prima devi aver creato il BOT su Telegram)

<code>https://api.telegram.org/bot256932411:AAFi0hEeve79ujB3i84ZkUYkJIVtBtTTFoE/sendMessage</code>

### Method

seleziona <code>POST</code>

### Content Type

seleziona <code>application/x-www-form-urlencoded</code>


### Body

inserisci l'id del canale che hai precedentmente creato su Telegram <code>chat_id=@AnsaSicilia&text= {{EntryTitle}} {{EntryUrl}}</code>

---

### <code>Semplici guide</code>
- https://www.piersoft.it/creare-canale-telegram-ed-alimentarlo-automaticamente-un-rss-feed/
- http://www.andreaminini.com/telegram/come-pubblicare-automaticamente-su-telegram-tramite-ifttt
- https://github.com/ondata/albo-pop/wiki/IFTTT#pubblicare-gli-aggiornamenti-di-un-feed-rss-su-un-canale-telegram
