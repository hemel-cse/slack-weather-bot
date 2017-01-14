# slack-weather-bot
## A simple slack bot that provide weather info from yahoo API 

### How to use:

Set an environment variable for your slack token, update the token name here 

```
  	slack_token := os.Getenv("YOUR_SLACK_TOKEN_HERE") 
```

And you are good to go, build and run the bot.go file, create a bot in your slack team
Add the bot to a channel and the type:

```
  @bot_name weather location_name
```
It'll sends message back to the channel containing weather info for the particular location. 
Let me know if you found something wrong or wanna update it you are welcome.



