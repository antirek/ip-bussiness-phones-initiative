

# Built-In HTTP API

Make calls, set on hold, resume, hangup calls, set status of phone via http requests.


## Scheme

In phone built in webserver which accept requests with parameters for some actions.



#### Call to number

http://{PHONE_IP_ADDRESS}/api?action=call&number=89135292926&line=1&token={TOKEN}

#### Set DND

http://{PHONE_IP_ADDRESS}/api?action=changestatus&status=dnd&token={TOKEN}

#### Forwarding

#### Hold

#### Hangup


## Security

OAuth2, password, ip white list
