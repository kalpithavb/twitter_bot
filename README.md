
# Create your own auto direct message Twitter Bot 

Create a welcome message for your new followers on twitter.

To develop this bot we need:

-   Node js installed
-   [Twit](https://medium.com/r/?url=https%3A%2F%2Fgithub.com%2Fttezel%2Ftwit) : Twitter API Client for node
-   [Github Account](https://medium.com/r/?url=https%3A%2F%2Fgithub.com%2F)
-   [Twitter Account](https://medium.com/r/?url=https%3A%2F%2Ftwitter.com%2F)
-   [Heroku Account](https://medium.com/r/?url=https%3A%2F%2Fwww.heroku.com%2F) to deploy the bot.

### Create your Own Twitter Bot 

#### Step 1: Github.

  Fork the project repo in Github
  Now, Customize your welcome message by updating the  `GenerateMessage` function and Commit your change.

#### Step 2 : Twitter

Create a Twitter app: Go to  [https://apps.twitter.com/](https://medium.com/r/?url=https%3A%2F%2Fapps.twitter.com%2F)  and click to the button  `Create New App`, then complete all the fields as the following:

Go to the  `Permissions`  section and give the app the access to send Direct messages by checking the option “Read, Write and Access direct messages”.

Go to tab `key and Access Tokens` then click the `Generate Access Token` button at the bottom of the page.

Now copy all your keys  `Consumer Key`,  `Consumer Secret` ,  `Acess Token`A and  `Acess Token Secret`, because we need to add all of them later as Heroku vars.

#### Step 3: Heroku

-   Create a  [Heroku account](https://medium.com/r/?url=https%3A%2F%2Fdashboard.heroku.com%2F). it is free!
-   Connect to your Heroku account and create a new app by clicking the  `New`button, then the  `Create new App`  option.
-   Choose your app name then click  `Create App`

Choose Github as the Deployment method then click the connect button

Tab your bot repo name : `twitter-bot ` in your case.

Now you need to add all keys as Heroku vars on the tab settings and config the Variables section.

Return to the deploy section and click “enable automatic deploys”, then “deploy branch” button to deploy your app for the first time.

Go to resources section and activate the worker Dyno and disable the web dyno.



