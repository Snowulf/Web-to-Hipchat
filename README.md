# Web-to-Hipchat
It's stupidly simple to use. Simply POST some JSON to the /hipchat endpoint. It wants the following values:

room - integer - room API ID
color - string - color for the message. One of: "yellow", "red", "green", "purple", "gray", or "random"
from - string - the name to send from
message - string - the message to send to the channel

## Example
curl -d '{"room": 100, "color": "green", "from": "FoxBot", "message": "Hello, world!"}' https://example.com:8443/hipchat

# Installation
Clone this repo; cd into it; run npm install
