## Marche à Suivre 

Lance @Godfather sur Telegram 
Run /newbot pour créer un bot et suis ce qu'il te dit.

### Vérifie que Node.Js & Npm sont installés: 
`node -v & npm -v`
### Va dans le dossier où se trouve le script.
`cd "C:\Users\Shin\Downloads\privatechat-tg.js" `
### Télécharge les différentes API de Telegram:
`npm install node-telegram-bot-api`
`npm install -g npm@11.10.0`
### Rentre ton token généré par @GodFather
`const token = 'Token généré par GodFather ici';` 
`node privatechat-tg.js`
### Dans la cmd après que tu aies envoyé le premier message via ton bot, il y aura un ChatId va se générer
Modifie alors la ligne "let ChatId = null;" en remplacant null par le nombre donné.

