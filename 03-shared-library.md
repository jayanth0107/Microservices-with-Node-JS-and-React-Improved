# [Stephen Grider] Microservices with Node JS and React [ENG, 2021]

<br/>

## 12. Code Sharing and Reuse Between Services

    $ cd app
    $ mkdir common
    $ cd common/
    $ npm init -y
    $ npm install --save-dev typescript del-cli

    $ tsc --init

<br/>

**tsconfig.json**

    "baseUrl": "./src"
    "declaration": true
    "outDir": "./build"

<br/>

    $ npm run build

<!--
<br/>

### 06. An Easy Publish Command

<br/>

    $ npm version patch
    $ npm run build

<br/>

### 07. Relocating Shared Code

```
auth/src/errors copy to common/src/errors
auth/src/middlewares copy to common/src/middlewares
```

<br/>

```
$ npm install --save \
    express \
    express-validator \
    cookie-session \
    jsonwebtoken \
    @types/cookie-session \
    @types/express \
    @types/jsonwebtoken
```

<br/>

    $ tsc

<br/>

    $ npm run publish

<br/>

### 08. Updating Import Statements

    $ cd auth
    $ npm install --save @grider-ms-tickets/common

<br/>

### 09. Updating the Common Module

    $ cd auth
    $ npm update @grider-ms-tickets/common -->

<br/>

---

<br/>

**Marley**

Any questions in english: <a href="https://jsdev.org/chat/">Telegram Chat</a>  
Любые вопросы на русском: <a href="https://jsdev.ru/chat/">Телеграм чат</a>