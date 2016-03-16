
# Call Hooks

Make http request from phone on incoming call, on answer, on hangup to some urls with call data .


## Scheme

Trigger on events in phone make request to hook url: incoming call - http request, user answer on call - http request.


#### On event trigger make request

http://{CUSTOM_IP_ADDRESS}/some_string/with/tokens/{TIME}/{NUMBER}/{LINEID}/{CALLID}/{HOOKTYPE}

where hooktype in ['in', 'answer', 'hangup', 'abandon']


## Security

check access on accepted side

set token hook url
