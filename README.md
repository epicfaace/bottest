info from https://docs.microsoft.com/en-us/bot-framework/nodejs/bot-builder-nodejs-quickstart

# Develop
* run ```node app.js```
* download bot framework emulator
* go to http://localhost:3978/api/messages on bot emulator.

# Deploy
* https://dev.botframework.com/bots/new -- make a new bot.
* create web app on http://portal.azure.com
* set up deployment options --> github
* application settings --> App Settings --> set values for MICROSOFT_APP_ID and MICROSOFT_APP_PASSWORD <img src="https://docs.microsoft.com/en-us/bot-framework/media/azure-secrets.png"/>
* open http://epicfaace-bot.azurewebsites.net/api/messages in bot emulator

* go back to dev.botframework website, set messaging endpoint to (HTTPS!) https://epicfaace-bot.azurewebsites.net/api/messages

# Connect with facbeook, etc.
* follow instructions in https://docs.microsoft.com/en-us/bot-framework/channel-connect-facebook