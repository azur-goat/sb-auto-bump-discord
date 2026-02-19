A selfbot that automatically bumps on Disboard.

# WARNING
Selfbots are against Discord's Terms of Service.
See more here : https://discord.com/guidelines https://discord.com/terms

This code is only for education.

If an account get banned or limited by Discord due to the use of this selfbot or breaking rules, it's not my problem.

# Setup
Open **.env**:
```
TOKEN=
BUMP_CHANNEL=
```
Put your account token to the end of **TOKEN=**

Put the ID of the channel that you want the bot to send **/bump** in to the end of **BUMP_CHANNEL=**

# How to get your user token
1. Open Discord PTB or Browser discord
2. Press `CTRL+SHIFT+I` to open the Console
3. Copy and paste the code below into the console to take your user token.
```js
window.webpackChunkdiscord_app.push([[Symbol()],{},o=>{for(let e of Object.values(o.c))try{if(!e.exports||e.exports===window)continue;e.exports?.getToken&&(token=e.exports.getToken());for(let o in e.exports)e.exports?.[o]?.getToken&&"IntlMessagesProxy"!==e.exports[o][Symbol.toStringTag]&&(token=e.exports[o].getToken())}catch{}}]),window.webpackChunkdiscord_app.pop(),token;
```
4. Then copy and paste your token.
5. Run the script
   
# How it works

Make sure that this script is **always on** to bump every time. ( If you can't make sur to add @ccuwu_ on discord, he will help you to get an host)
It will connect to your account.
And it will send a message in the id of the channel that you choose and send randomly every 2-3hours the command **/bump**
