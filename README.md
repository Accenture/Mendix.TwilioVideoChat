## TwilioVideoChat
Mendix widget for Twilio Video chats

## Usage
Place the widget on a Data View returning any entity that can provide configuration values for:
- Room name
- Nick name (identity)
- Join room (boolean; on true will join the room, on false will leave it)
- Access Token string. You can generate it using our helper Java Action: GenerateAccessToken in TwilioAccessTokenGenerator module.

In order to use it, you have to have a [Twilio account](https://www.twilio.com/try-twilio) and:

- Account SID: Your primary Twilio account identifier - find this [in the console here](https://www.twilio.com/console).
- API Key SID: Used to authenticate - [generate one here](https://www.twilio.com/console/runtime/api-keys).
- API Key Secret: Used to authenticate - [just like the above, you'll get one here](https://www.twilio.com/console/runtime/api-keys).

## Demo project
[twiliovideochat-sandbox.mxapps.io](https://twiliovideochat-sandbox.mxapps.io/)
