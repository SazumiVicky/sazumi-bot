<h3>SAZUMI-BOT (BETA VERSION)</h3>

![sazumi-bot](https://cdn.jsdelivr.net/gh/SazumiVicky/sazumi-bot@main/storage/20230810_130446.jpg)

##

<h4>What is sazumi-bot ?</h4>
<p>Sazumi-bot is a multi-device WhatsApp bot that is derived from the Ayaka V2 package, more precisely, sazumi-bot is the upcoming version that will be enhanced and will become the stable version.</p>

##
<h>**config.js**</h2>

```javascript
global.owner = ['6285236226xxx']; // Your number is here
global.mods = ['6285236226xxx']; // Your number is here
global.prems = ['6285236226xxx']; // Your number is here

global.nameowner = 'Sazumi Viki'; // Owner name
global.numberowner = '6285236226xxx'; // Owner number
global.mail = 'root@sazumi.moe'; // Owner E-mail

global.namebot = '🐱 Sazumi - Bot Whatsapp'; // Bot name
global.gc = 'https://chat.whatsapp.com/I057peOL7sK7v1jqcTEXoZ'; // Url group
global.web = 'https://chat.whatsapp.com/I057peOL7sK7v1jqcTEXoZ'; // Site url
global.instagram = 'https://instagram.com/moe.sazumiviki'; // Instagram url account

global.lolkey = 'YOUR_LOLKEY'; // LoL Human Api
global.sazumiviki_title = '🐱 Sazumi - Bot Whatsapp' // Title Here
global.sazumiviki_thumb = 'https://cdn.jsdelivr.net/gh/SazumiVicky/sazumi-bot@main/storage/20230810_130446.jpg' // Thumbnail url here
global.sazumiviki_source = 'https://instagram.com/moe.sazumiviki' // Source Url Here
global.sazumiviki_profile = 'https://cdn.jsdelivr.net/gh/SazumiVicky/Storage@main/510e37bebbf7a780e7ade93a66f268ff.jpg' // Profile url here
global.sig = 'https://instagram.com/moe.sazumiviki' // Instagram url here
global.sazumi_version = '© sazumi-bot v1.0.1 (Beta)' // Title bot here
global.footer = '≈ ꜱᴀᴢᴜᴍɪ-ʙᴏᴛ ᴄʀᴇᴀᴛᴇᴅ ʙʏ ꜱᴀᴢᴜᴍɪ ᴠɪᴋɪ' //  Footer bot here
global.wm = '🐱 Sazumi - Bot Whatsapp'; //  Watermak here
global.watermark = wm; // Watermak here
global.wait = 'Wait a moment..'; // Message waiting here
global.sazumiviki_imgur = 'Client-ID 5f98ee8de4fa3c5'; // Dont change
global.skizo = 'YOUR_KEY_HERE'; // Your key skizo apis
global.sourceUrl = 'https://Instagram.com/moe.sazumiviki'; // Source url

global.stiker_wait = 'Wait a moment..'; // Sticker message waiting here
global.packname = '@moe.sazumiviki'; // Sticker packname
global.author = 'sazumi-bot\n'; // Sticker author name

/*
* This section is down, don t change it
*/

global.APIs = {
  lolhuman: 'https://api.lolhuman.xyz',
  skizo: 'https://skizo.tech/',
  sazumiviki: 'https://api.sazumiviki.moe'
};

global.APIKeys = {
  'https://api.sazumiviki.moe': 'sazumiviki',
  'https://skizo.tech': 'sazumiviki',
  'https://api.lolhuman.xyz': 'sazumiviki',
};

global.multiplier = 45;
global.rpg = {
  emoticon(string) {
    string = string.toLowerCase();
    let emot = {
      exp: '✉️',
      money: '💵',
      potion: '🥤',
      diamond: '💎',
      common: '📦',
      uncommon: '🎁',
      mythic: '🗳️',
      legendary: '🗃️',
      pet: '🎁',
      sampah: '🗑',
      armor: '🥼',
      sword: '⚔️',
      kayu: '🪵',
      batu: '🪨',
      string: '🕸️',
      kuda: '🐎',
      kucing: '🐈',
      anjing: '🐕',
      petFood: '🍖',
      gold: '👑',
      emerald: '💚'
    };
    let results = Object.keys(emot).map(v => [v, new RegExp(v, 'gi')]).filter(v => v[1].test(string));
    if (!results.length) return '';
    else return emot[results[0][0]];
  }
};

let fs = require('fs');
let chalk = require('chalk');
let file = require.resolve(__filename);
fs.watchFile(file, () => {
  fs.unwatchFile(file);
  console.log(chalk.redBright("Update 'config.js'"));
  delete require.cache[file];
  require(file);
});
```
##

<h4>How much does sazumi-bot script cost?</h4>

- 🏷️ IDR **Rp 100.000** / **$7,22** Free Update 2x</b>
- 🏷️ IDR **Rp 60.000** / **$3,85** Free Update 1x</b>

##

<h4>Bot Code Type</h4>

- <b>Plugins</b>
- ~Case~

##

**Benefits**
- [x] Free updates according to plan
- [x] Free [LoL Human REST APIs](https://api.lolhuman.xyz) [ **1month** / **2month** ]
      
##

<h4>Where can I buy sazumi-bot script officially?</h4>

- [Whatsapp](https://wa.me/6285236226786)
- [Telegram](https://t.me/sazumiviki)

##

<h4>Read this before purchasing the script</h4>

- Should I understand programming?
   - Yes, you should be able to master basic JavaScript & Node.js.

- Can I get a refund once I've received the script?
   - No, I do not accept refund requests.
 
- Are there any plugins that are encrypted?
   - Adding encryption to certain parts of the code in plugins, in order to prevent unauthorized transactions.

- Can I request a feature?
   - Yes, you are free to request any feature, but I may not necessarily develop it, though I will do my best.

- Is it possible to negotiate the price of the script?
   - No, I do not accept price negotiations.

- Can I get the script for free?
   - No, I do not provide the script for free

- How many times can I change my IP address?
   - You can change your IP address up to 5 times.

- When I have used all of my IP addresses, will there be a charge to obtain more IP slots?
   - Yes, you will incur an additional fee to obtain more IP slots. The cost for 1 IP slot is **Rp 15.000,00** / **$1**.

- Will I get the werewolf and blackjack features as well?
   - I'm sorry, I haven't published the werewolf and blackjack features yet.
 
- Which features do you encrypt?
   - I encrypted the **index.js**, **print.js**, and **viki-regmail.js** files **(97% Not Encrypted)**.

- Why did you encrypt the code?
   - I encrypted the code to prevent it from being sold, and the encrypted code doesn't contain any watermark within the text message.

- Am I allowed to share plugins, code, and bot api keys with others?
   - No, I strongly prohibit that.

- Should I keep my old IP?
   - Yes, to obtain a free IP replacement, once it's no longer available, you will need to pay **Rp 15.000,00** / **$1** to purchase one IP slot.
 
- How do I allow my IP?
   - Set your IP address on the sazumi-bot by sending the command **".setip xxxxx"**
   - To view your sazumi-bot account, simply send the message **".account."**

##

<h4>The script is supported to run on:</h4>

- [x] Rdp
- [x] Vps
- [x] Kinsta 
- [x] Railway
- [x] Panel Pterodactyl  

##

<h4>Minimum specifications required</h4>

- [x] **Node Version:** 18.18.2
- [x] **Npm Version:** 9.8.1
- [x] **Cpu:** 400%
- [x] **Memory:** 4GB
- [x] **Disk:** 10GB

##

<h4>Recommendations specifications required</h4>

- [x] **Node Version:** 18.18.2
- [x] **Npm Version:** 9.8.1
- [x] **Cpu:** 800%
- [x] **Memory:** 8GB
- [x] **Disk:** 50GB

##
README

- [x] Use your own rose APIs [ITSROSE - APIs](https://api.itsrose.life)
- [x] All terms are subject to change at any time, and you must adhere to the new regulations. 

##

Demo : [sazumi-bot v1.0.1](https://wa.me/62857961868359?text=.menu)
<br>
Creator : [Sazumi Viki](https://wa.me/6285236226786)
<br>
Official Group : [Sazumi Bot - Public](https://chat.whatsapp.com/H35sD41KBF53oJ1hPiSN69)

##

<h4>Latest changelog update</h4>

| ChangeLog | Published On |
| ----- | ------------ |
|  Added new **image format** features| Mon Nov 20 2023 |
|  Fixed **ytmp4** and **ytmp3**| Sat Nov 18 2023 |
|  Adding a fake number feature for several of its countries **( . fakenumber )**| Sun Oct 01 2023 |
|  Addition of random visa card feature **( .card )**| Sun Oct 01 2023 |
|  Create a sticker feature to support **gifs** & **videos**| Thu Sep 21 2023 |
|  Fixed **tiktok-stalk** to a better version| Thu Sep 21 2023 |
|  Making **igstory** better| Thu Sep 21 2023 |
|  Fix Fix Erorr **IgStalk**| Mon Sep 18 2023 |
|  Fix **Shortlink**| Mon Sep 18 2023 |
|  Adding the **blackbox** chat AI feature| Sat Sep 16 2023 |
|  Fix **TikTok Downloader**| Sat Sep 16 2023 |
|  Adding the **outpainting** feature.| Wed Sep 06 2023 |
|  Adding send in document form to, **play, ytmp3, and ytmp4,** using the argument **--doc** behind the text.| Sun Sep 03 2023 |
|  New feature, **create subdomains** and **delete subdomains** ( cloudflare )| Tue Aug 22 2023 |
|  Fixed **simi simi** features| Tue Aug 22 2023 |
|  Fix **Antiporn**| Mon Aug 21 2023 |
|  Fixed the **pairing code** error when entering the **pairing code**| Fri Aug 18 2023 |
|  Added features **Tebak Bom**| Fri Aug 18 2023 |
|  Fixed **Backup** Feature on Bot| Thu Aug 17 2023 |
|  Updating the data on the **lyric feature**| Tue Aug 15 2023 |
|  Added **ram** usage **limit**| Tue Aug 15 2023 |
|  Add Feature **Tts**| Mon Aug 14 2023 |
|  New Feature **Compress Image**| Sun Aug 13 2023 |
|  New Feature **Deepfake**| Sun Aug 13 2023 |
|  New Sticker Feature **.snobg (Sticker without background)** & **.scircle (Circle shape sticker)**| Sun Aug 13 2023 |
|  Remove **Bard Ai**| Sat Aug 12 2023 |
|  Fix **Emojimix**| Fri Aug 11 2023 |
|  Starting **sazumi-bot version 1.0.0** and onwards| Thu Aug 10 2023 |

