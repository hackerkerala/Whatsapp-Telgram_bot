<h1 align="center">
 
<b>TELEGRAM WHATSAPP BOT</b>
</h1>
<h4 align="center">Yet another userbot for Whatsapp</h4>
<br>

<br>

### Features :

- Modular
- Get WhatsApp messages on Telegram as soon as they arrive
- Reply on WhatsApp by replying to the message on Telegram.
- Easily Deployable
- Ban Free (Using Whatsapp Web)
- Easy to Use
- Terminal Included

### Pre Added Plugins :

- **term** - Terminal in Whatsapp  
- **sticker** - Convert image to sticker
- **carbon** - Create beautiful images using carbon.now.sh
Soon adding more!

### Deploy :

##### - Heroku
[![Deploy with Heroku](https://www.herokucdn.com/deploy/button.svg "Deploy with Heroku")](https://heroku.com/deploy?template=https://github.com/ALBINPRAVEEN/Whatsapp-Telgram_bot "Deploy with Heroku")<br>
<!--- Deploy to Railway -->
##### - Railway
###### Method 1 (Recommended):
- Fork this repo.
- Now head towards https://railway.app/new, select Deploy from repo.
- Now select the forked repository, select branch.
- Now go to <b>Variables</b> and add variable listed below.
   - DB_URL, PMGUARD_ENABLED, REMOVE_BG_API, TG_BOT_TOKEN, TG_OWNER_ID
- Go to <b>Deployments</b> and for deplyment to complete.
- Now you'll get qr code on tg bot, scan it and you're good to go.
 
###### Method 2:
[![Deploy+on+Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/ALBINPRAVEEN/Whatsapp-Telgram_bot&envs=DB_URL,PMGUARD_ENABLED,REMOVE_BG_API,TG_BOT_TOKEN,TG_OWNER_ID&DB_URLDesc=Create+A+Database+In+Mongodb+And+Get+URL.&PMGUARD_ENABLEDDesc=Put+true+to+enable+Pm+Guard.+Default+is+false.&REMOVE_BG_APIDesc=Remove.bg+API+key.+Get+it+from+https://remove.bg&TG_BOT_TOKENDesc=Get+Your+Bot+Token+From+@BotFather.&TG_OWNER_IDDesc=Your+telegram+ID.+Get+your+id+from+@userinfobot)


### Commands

_Send <code>!help</code> in Anywhere._

### Working :

- Opens whatsapp web in server using puppeteer.
- Listen messages and take action.

### Credits :

- [Whatsapp Web JS](https://github.com/pedroslopez/whatsapp-web.js/ "Whatsapp Web JS") - This project is fully depended on this awsome Library.
- [Js Dh](https://t.me/GcamMasterRace) for WhatsGram banner and icon.

