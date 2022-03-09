# The WebSocket Chat assignment done at NTNU: 
Whiteboard with client websocket service

Chat #1

![image](https://user-images.githubusercontent.com/72363251/157536422-96b9ca96-e1d6-4cc1-8e43-2b1a82030128.png)

Chat #2

![image](https://user-images.githubusercontent.com/72363251/157536529-61dd1ec2-7214-43ab-909d-31c9cfa89113.png)

## Setup database connections

This example does not use any database. You can therefore create empty `config.ts` files:

```sh
touch server/config.ts server/test/config.ts
```

## Start server

Install dependencies and start server:

```sh
cd server
npm install
npm start
```

### Run server tests:

```sh
npm test
```

Compared to the previous example project, the only additional dependency is
[ws](https://www.npmjs.com/package/ws).

## Bundle client files to be served through server

Install dependencies and bundle client files:

```sh
cd client
npm install
npm start
```

### Run client tests:

```sh
npm test
```
