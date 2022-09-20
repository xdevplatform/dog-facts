# Tweet a dog fact

Allows you to Tweet a fact about dogs once! Try it out at [tweet-a-dog-fact.glitch.me](tweet-a-dog-fact.glitch.me).

This site walks you through the OAuth 2.0 Authorization Code Flow with PKCE for authentication and makes a call to the Twitter API's manage Tweets endpoint.

## A framework

This code sample can be a starting point to make a bot similar to [@Factual\_\_Dog](https://twitter.com/Factual__Dog), a bot that Tweets dogs facts twice daily. This can be remixed to make your own bot, if you do you will need to add in your own logic to determine how often your bot will Tweet.

## Prerequisites

In order to remix this code sample you will need the following:

- A developer account.
  - If you don’t already have access to the Twitter API, [you can sign up for a developer account.](http://t.co/signup)
- A Project in the [developer portal](https://developer.twitter.com/en/portal/dashboard)
- An App containing the credentials required to use the Twitter API
- OAuth 2.0 turned on in your App’s authentication settings
- You will also need to update your `.env` file to include your client ID, client secret and redirect URI. You can obtain your client ID and secret from your App's authentication settings and your redirect URI should be `your-glitch-project.glitch.me/oauth/callback`. This must match the redirect URI in your App's authentication settings.
