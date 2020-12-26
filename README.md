# DISCORD-ART

<p>
  <img alt="Version" src="https://img.shields.io/npm/v/discord-art?style=for-the-badge" />
</p>

> **Ce module vous permet de transformez vos textes en caractères spéciaux parfois amusant !**

## Installer le module
```
npm i discord-art
```

## Utilisation
Ce module **très simple d'utilisation** vous permettra de transformez votre texte en symboles spéciaux tels que blocks, ascii-art, bold,... Tout cela en une seule ligne !
```js
const art = require("discord-art");
const Discord = require('discord.js');

const client = new Discord.Client();

const settings = {
  token: "YOUR_DISCORD_BOT_TOKEN",
  prefix: "YOUR_DISCORD_BOT_PREFIX"
};

// Transformation en block :
client.on('message', async message => {
  if(message.content.startsWith(settings.prefix + "block") {
    message.channel.send(art.block("YOUR_TEXT"))
  }
});

client.login(settings.token);
```

## Auteur
> **Luztog** | Discord: **Luztog#1910** (ID: `502159636175257600`)

* GitHub : [Cliquez ici](https://github.com/Luztog)

## 📝 License
© Luztog#1910 - 2020-2021

> Ce projet est sous license **MIT**.
