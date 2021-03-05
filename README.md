# twitbot - I am Cook Eat Cook Bot

The fun-key cookeatcook.com Twitter bot https://twitter.com/cookeatcook1

I cook.

# Install Nodejs

brew install node

git clone https://github.com/starfrosch/cookeatcooktwitbot.git

# Configure

Add your tokens and secrets from http://apps.twitter.com to config.js

```javascript
//config.js
/** TWITTER APP CONFIGURATION
 * consumer_key
 * consumer_secret
 * access_token
 * access_token_secret
 */

module.exports = {
  consumer_key: '',
  consumer_secret: '',
  access_token: '',
  access_token_secret: ''
}
```

Modify your twitter search terms and time intervals in bot.js

# Run

node bot.js

# Deploy to Heroku

https://devcenter.heroku.com/articles/deploying-nodejs

