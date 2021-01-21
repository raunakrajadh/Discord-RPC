# Discord - RPC

A way of making custom rpc on Discord using Node.js

<li>What are the steps to make it work?
<li>How to configue the rpc?

## What are the steps to make it work?

1. Go to <a href="https://discord.com/developers/applications">Discord Developer Potal</a>
2. Make a new Application (__The name of application is the name of our RPC__)
3. Navigate to Rich Presence🟢 and navigate to Art Assets🔵

<img src="https://media.discordapp.net/attachments/755031719811481601/801731202045968384/unknown.png?width=1189&height=588"></img>

4. Add your rpc icon through Add Image🔴 and remember the name given to it. (For instance; name == 🧿)

## How to configure the rpc?

1. Setup/Install the denendencies

Open termina, navigate to your folder and run the following!

```
npm install
npm install discord-rpc
```

2. Configure rpc

<li>Open your code editor and open 'config.json' file.

```json
{
    "botId": "Application ID",
    "details": "Enter the detail that your want to show in your RPC",
    "state": "Enter the state of you doing something to display in your RPC",
    "largeImageKey": "Enter the name of the icon you added :-🧿-:",  //How to configure the bot, Step-4
    "largeImageText": "Raunak || Bot Labs"
}
```

3. Startup

```
node index.js
```