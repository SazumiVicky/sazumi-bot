<h2>SAZUMI-BOT (BETA VERSION)</h2>

![sazumi-bot](https://cdn.jsdelivr.net/gh/SazumiVicky/sazumi-bot@main/storage/20230810_130446.jpg)

##

<h4>What is sazumi-bot ?</h4>
<p>Sazumi-bot is a multi-device WhatsApp bot that is derived from the Ayaka V2 package, more precisely, sazumi-bot is the upcoming version that will be enhanced and will become the stable version.</p>

##
<h>config.js</h2>

```javascript
global.owner = ['6285236226786']; // Your number is here
global.mods = ['6285236226786']; // Your number is here
global.prems = ['6285236226786']; // Your number is here

global.nameowner = 'Sazumi Viki'; // Owner name
global.numberowner = '6285236226786'; // Owner number
global.mail = 'hi@sazumiviki.dev'; // Owner E-mail

global.namebot = '🐱 Sazumi - Bot Whatsapp'; // Your bot name
global.gc = 'https://chat.whatsapp.com/LqvyPGgU82ZHogxjpU60BE'; // Your group
global.web = 'https://chat.whatsapp.com/LqvyPGgU82ZHogxjpU60BE'; // Your site
global.instagram = 'https://instagram.com/moe.sazumiviki'; // Your instagram account

global.lolkey = 'xxxxxx'; // Your LoL Human Api
global.sazumiviki_title = '🐱 Sazumi - Bot Whatsapp' // Your Title Here
global.sazumiviki_thumb = 'https://cdn.jsdelivr.net/gh/SazumiVicky/sazumi-bot@main/storage/20230810_130446.jpg' // Thumbnail Url Here
global.sazumiviki_source = 'https://instagram.com/moe.sazumiviki' // Your Source Url Here
global.sazumiviki_profile = 'https://cdn.jsdelivr.net/gh/SazumiVicky/Storage@main/510e37bebbf7a780e7ade93a66f268ff.jpg' // When there is no profile photo
global.sig = 'https://instagram.com/moe.sazumiviki' // Your instagram url
global.footer = '≈ ꜱᴀᴢᴜᴍɪ-ʙᴏᴛ ᴄʀᴇᴀᴛᴇᴅ ʙʏ ꜱᴀᴢᴜᴍɪ ᴠɪᴋɪ' // Your Bot Footer
global.wm = '🐱 Sazumi - Bot Whatsapp'; // Watermak 
global.watermark = wm; // Dont Change This
global.wait = 'Wait a moment..'; // Dont change this
global.sazumiviki_imgur = 'Client-ID xxxxxxxxxxxxx'; // Your imgur Client-iD Here: https://api.imgur.com/oauth2/addclient
global.rose = 'Rs-xxxxxxx'; // Your Rose apikey
global.xzn = 'xxxxxxxxxx'; // Your xzn apikey
global.sourceUrl = 'https://Instagram.com/moe.sazumiviki'; // Your source url

global.stiker_wait = 'Wait a moment..'; // Dont change this
global.packname = '@moe.sazumiviki'; // Your packname sticker
global.author = 'MakeMeow\n'; // Your Author sticker

/*
* This section is down, don t change it
*/

global.APIs = {
  lolhuman: 'https://api.lolhuman.xyz',
  rose: 'https://api.itsrose.life',
  rey: 'https://api.sazumiviki.me'
};

global.APIKeys = {
  'https://api.sazumiviki.me': 'sazumiviki',
  'https://api.itsrose.life': 'sazumiviki',
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
