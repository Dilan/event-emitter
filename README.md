# Event Emitter

### Install

    $ npm i

### Run server

    $ npm start

### Docker / Mongodb

    $ docker pull mongo:4.4
    $ docker run -p 127.0.0.1:27017:27017  --name mongo  -v ~/mongodb/:/data/db  -d mongo:4.4


###  API

get all users:

    $ curl http://127.0.0.1:5001/api/users

add user:

    $ curl -X POST http://127.0.0.1:5001/api/users -H 'Content-Type: application/json' -d '{ "name": "Anton", "department":"Software" }'

