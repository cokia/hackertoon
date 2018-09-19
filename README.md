
# 2018 부산시 학생 해커톤

- We used Chat.js made by tegioz
- <string>Chat.JS : github.com/tegioz/chat
  
### Built with:
  - <string>main chat : github.com/tegioz/chat
  - <strong>Server side:</strong> Node.js, Socket.io, Express, Redis 
  - <strong>Client side:</strong> HTML5 Boilerplate, Bootstrap, Handlebars and jQuery

### Requires

  - Node.js
  - NPM (Node Package Manager)
  - Redis

### Run

Fetch dependencies:

    npm install

Launch Redis:
    
    redis-server

Launch chat server:
    
    (don't forget to launch Redis before!)

    node chatServer.js

Now open this URL in your browser:

    http://localhost:8888/

and you're done ;)

### Broadcast API

Send messages to all connected users:

    Content-Type: application/json
    POST /api/broadcast/

    {"msg": "Hello!"}
