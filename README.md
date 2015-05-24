# imma-let-you-finish

![](http://ledhack.org/content/images/2015/05/imma-let-you-finish.png)

[imma-let-you-finish](http://ledhack.org/imma-let-you-finish/) celebrates over five years of [Kanye West hacking the stage](https://www.youtube.com/watch?v=3K21rLBEfeM). This [Slack Bot](https://slack.com/) will randomly appear on your conversation to tell everyone who has the best comment of all times. Of all times!

## Add it on your Slack channel in three steps!
### Step 1 - Create an Outgoing Webhook integration
You'll need to go to https://TEAM-DOMAIN.slack.com/services/new/outgoing-webhook and add a new Outgoing Webhook integration. 

Select a channel where you want Kanye West to hang out. I'm using #general, for example. Additionaly, there is a Token on the Integration Settings section. Copy that value. You'll need it later.

Keep this browser tab open, because we will come back to it later.

![Outgoing Webhook Token](http://i.imgur.com/tn6Kfgzl.png)

### Deploy this app to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/sparragus/imma-let-you-finish/tree/master)

Use that button to deploy this app to Heroku. Before you deploy the app, add the Outgoing Webhook Token for the config variable. Also, give your app a name.

![Outgoing Webhook Token config variable](http://i.imgur.com/iIcRr5yl.png)

### Add the app's URL on the Outgoing Webhook Integration.
Your app should have a URL. If you don't know it, you can find it on Heroku under your app's settings. Take note of it.

Now go back to the integration settings. Add the URL. Save your settings.

![Slack Integration URL](http://i.imgur.com/5GAHS9ol.png)

### You're done! :D
Kanye West has a 0.5% of interrupting your conversations. A rare sight, indeed. But when he appears, lols are guaranteed.

![](http://ledhack.org/content/images/2015/05/taylorkanye-1.gif)