# ShinobuMemes-dev
Shinobu Memes es un modulo que cuenta con memes variados!. Perfecto para tú bot de discord!
# Instalación
```npm i shinobu-memes```
# Uso
```js
const momos = require('shinobu-memes');//Requerimos el paquete
const meme = momos.Shinobumemes()
console.log(meme)//Retorna los memes qué tenemos por el momento ^^
```
# Ejemplo
```js
const a = require('shinobu-memes')

const meme = a.Shinobumemes()

const Discord = require('discord.js');
const client = new Discord.Client({
    intents: 98047
})
client.on('ready', () => {
    console.log(meme)
});

client.on('message', (message) => {
    if (message.content == 'meme') {
       message.channel.send(`${meme}`)
    }
});

client.login('token');//El token es extraido de developer portal de discord ^^
```
# Opciones
`<meme>.Shinobumemes` Retorna memes en español por el momento(Proximamente agregaremos videos y memes en ingles^^)
# Links
[**Discord server**](https://discord.gg/vBEpM5258V)

# Agradecimientos
Tú ♥ ^^

# Notas de la nueva versión
Añadidas:
...
Reparadas:
README.md
Eliminadas:
...

# Noticias!
¡Nada por el momento!

