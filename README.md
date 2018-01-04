####  bot using -api.ai and twilio 
======================
Create an agent on API.AI and then create some intents and entities. I have created an agent for assiting in booking hotels.

![api ai agent](https://user-images.githubusercontent.com/17767383/27009877-8db61d10-4eb6-11e7-86d1-91df078f409f.png)

Now the next part is to integrate it with twilio messaging platform 
On configuring twilio you will get

Secret Instance SID

Account SID

API Key SID

API Secret

Fill the required fields in API.AI and host your chathot on heroku.

Once the bot has statred run the demo given below

### Running the demo

##### Set credentials

1. Copy `credentials.example.json` to `credentials.json`
2. Plug your credentials into `credentials.json`

##### Install dependencies

```
$ npm install
```

##### Run server

```
$ npm start
```

##### Connect

Connect via `http://localhost:8080`

![github twilio](https://user-images.githubusercontent.com/17767383/27009957-e13b8f3c-4eb7-11e7-96cd-cd733c3e9a5b.png)

```
