# Usage

```bash
curl http://localhost:8080/ -F From=+1234567890 -F Body=Hello
```
```bash
<?xml version="1.0" encoding="UTF-8"?>
<Response>
  <Message>Hello from Twilio. You've sent 1 message, and this one said 'Hello'</Message>
</Response>
```



## For public hosting with Java
[ngok](https://ngrok.com/)

```bash
ngrok http 8080
twilio phone-numbers:update PHONE_NUMBER --sms-url http://localhost:3000/messages

```

## License
[Twilio](https://www.twilio.com/blog/receive-respond-sms-java-twilio)
