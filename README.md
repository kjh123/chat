chat project


## Get Start

1. git clone https://github.com/kjh123/chat.git

### backend
* cd chat/backend
* docker build -t chat .
* docker run -d -ti -p 8080:8080 chat:latest

### frontend
* cd chat/fronted
* yarn
* npm start