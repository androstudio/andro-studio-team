Programmable Voice: Quickstart Application Server - Python
===
This repository contains the server-side web application required to run the [Twilio Programmable Voice iOS SDK Quickstart](https://www.twilio.com/docs/api/voice-sdk/ios/getting-started) and [Android SDK Quickstart](https://www.twilio.com/docs/api/voice-sdk/android/getting-started) mobile sample apps, written in Python.


### Deploy to the cloud using [Heroku](https://heroku.com)

Don't want to run the application server locally? You can also deploy it to the cloud using Heroku. Note: For this option, you'll want to gather your Twilio Account SID, API Key, API Key Secret, Push Credential SID and TwiML App SID before beginning the installation. (Don't know what these are? Read through the [Programmable Voice iOS SDK Quickstart](https://www.twilio.com/docs/api/voice-sdk/ios/getting-started) or [Programmable Voice Android SDK Quickstart](https://www.twilio.com/docs/api/voice-sdk/android/getting-started) for all the information.

If you don't already have one, visit Heroku and create a free account. Once that's done, click the button below to automatically set up this app, and enter the Twilio account information you gathered above when you're prompted.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

Test the app
---

Test your app by opening the `/accessToken` endpoint in your browser (use the publicly accessible domain on Heroku or Ngrok, whichever you chose above). You should see a long string. This is an Access Token. You can examine its contents by pasting it into a JWT tool like [jwt.io](http://jwt.io).

Confused?
---

Read through the instructions in the [iOS Getting Started](https://www.twilio.com/docs/api/voice-sdk/ios/getting-started) or [Android Getting Started](https://www.twilio.com/docs/api/voice-sdk/android/getting-started) guides. Still having trouble? [Email us and we'll give you a hand.](mailto:help@twilio.com)

License
---
AST
