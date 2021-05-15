[IFTTT](https://ifttt.com/home) per creare canale [Telegram](https://desktop.telegram.org/) con i feed [RSS](https://it.wikipedia.org/wiki/RSS)
=======
agganciare un feed RSS ad un canale Telegram grazie al servizio web di IFTTT

## Edit Applet

[**create**](https://ifttt.com/create) 

cerca <code>RSS</code>

# New feed item

## Feed URL

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/if.png"></p>

inserisci il link del feed RSS https://feedpress.me/gds_hp_palermo (url del feed RSS)


↓ su IFTTT cerca il componente editando "make a web request"

<p><img src="https://raw.githubusercontent.com/cirospat/ifttt_e_canale_telegram/main/img/then.png"></p>



# Make a web request

### URL:

digita il link dell'API che ti fornisce il BOT  che hai creato grazie a Bot father su Telegram (prima devi aver creato il BOT su Telegram)

<code>https://api.telegram.org/bot256932411:AAFi0hEeve79ujB3i84ZkUYkJIVtBtTTFoE/sendMessage</code>

### Method

seleziona = <code>POST</code>

### Content Type

seleziona = <code>application/x-www-form-urlencoded</code>


### Body

inserisci l'id del canale che hai precedentmente creato su Telegram inserendo la seguente sintassi = <code>chat_id=@AnsaSicilia&text= {{EntryTitle}} {{EntryUrl}}</code>

dove @AnsaSicilia è un nome del canale Telegram precedentemente creato dove si vuole che vengano pubblicati i feed RSS 

---

### <code>Semplici guide per creare canali Telegram che si alimentano dai feed RSS grazie al servizio di IFTTT</code>
- https://www.piersoft.it/creare-canale-telegram-ed-alimentarlo-automaticamente-un-rss-feed/
- http://www.andreaminini.com/telegram/come-pubblicare-automaticamente-su-telegram-tramite-ifttt
- https://github.com/ondata/albo-pop/wiki/IFTTT#pubblicare-gli-aggiornamenti-di-un-feed-rss-su-un-canale-telegram


---

# Per collegare un fedd <code>RSS</code> ad una canale Telegram, il serviziodi **IFTTT** prevede ora la possibilità di selezionare nella ricetta direttamente **Telegram**.
