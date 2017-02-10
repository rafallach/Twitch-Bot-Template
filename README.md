# Twitch Bot Template
(Yet another) Starting point for your Twitch Bot

### How To
1. Clone repo
2. Install tmi.js (npm install)
3. Update config:
+ `username` - Yours or your bot Twitch username
+ `password` - OAuth token. Visit: [http://www.twitchapps.com/tmi](http://www.twitchapps.com/tmi)
+ `channels` - Array with channel names your bot will join
4. Run: `node app.js`

Feel free to add new commands and options. I've used JS Map for commands which may be not the best choice but it's just a template for your app.

For detailed look on tmi.js visit [tmi.js repo](https://github.com/tmijs/tmi.js) or [documentation](https://docs.tmijs.org/).
