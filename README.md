# Chad's Twilio Lookup

Startup is not yet automated.

## (1) Start the lookup app

```
cd ~/Code/flex-lookup
npx http-server -p 8081
```

Now the node.js server for the custom lookup site is listening on port 8081.

## (2) Start the local Flex dashboard

```
cd ~/Code/flex-plugin/plugin-sample
npm start
```

Now the local Flex dashboard is running on port 8080.
Login with normal Flex credentials.

## (3) Load the site

http://localhost:8080/agent-desktop

## (4) Call the site

It only works with phone calls. It does not work with SMS.

Call your Twilio Flex inbound phone number.

## Notes

You don't need `ngrok`.

It won't work from the standard Twilio Flex dashboard on flex.twilio.com.
You need to run it locally.
