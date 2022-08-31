## Let's get started with using APIs
  


And what better way to learn than to impliment, right?  
I am following the [official documentation](https://www.twilio.com/docs/sms/quickstart/node#install-nodejs-and-the-twilio-module) to get it right.
  
```bash
npm install twilio
npm install dotenv
```

After setting up the enviroment variables, you can fire up the api with
```bash
node -r dotenv/config send_sms.js
```
  
>Or you may want to just __require('dotenv').config()__ in your code  
> to use node send_sms.js