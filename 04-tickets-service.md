# [Stephen Grider] Microservices with Node JS and React [ENG, 2021]

<br/>

## 13. Create-Read-Update-Destroy Server Setup

    $ cd app
    $ mkdir tickets

copy some files from auth project

    $ npm install

<br/>

    $ npm run test

<!-- <br/>

### 19. Better Error Logging

    $ cd common
    $ npm run publish

<br/>

    $ cd tickets
    $ npm update @grider-ms-tickets/common

<br/>

<br/>

```
// SIGN UP
$ curl \
--insecure \
--cookie-jar /tmp/cookies.txt \
--data '{"email":"marley@example.com", "password":"123456789"}' \
--header "Content-Type: application/json" \
--request POST https://ticketing.dev/api/users/signup \
| python -m json.tool
```

<br/>

```
// SIGN IN
$ curl \
--data '{"email":"marley@example.com", "password":"123456789"}' \
--header "Content-Type: application/json" \
--request POST http://ticketing.dev/api/users/signin \
| python -m json.tool
```

<br/>

```
// GET CURRENT USER
$ curl \
--insecure \
--cookie /tmp/cookies.txt \
--header "Content-Type: application/json" \
--request GET https://ticketing.dev/api/users/currentuser \
| python -m json.tool
```

<br/>

```
// CREATE TICKET
$ curl \
--insecure \
--cookie /tmp/cookies.txt \
--data '{"title":"concert", "price":10}' \
--header "Content-Type: application/json" \
--request POST https://ticketing.dev/api/tickets \
| python -m json.tool
```

<br/>

**response:**

```
{
    "__v": 0,
    "id": "5ebaa8a74cea0900186b7ec8",
    "price": 10,
    "title": "concert",
    "userId": "5ebaa6a3fc342b0023ded8a4"
}
```

<br/>

```
// GET TICKET
$ curl \
--insecure \
--header "Content-Type: application/json" \
--request GET https://ticketing.dev/api/tickets/5ebaa8a74cea0900186b7ec8 \
| python -m json.tool
```

<br/>

**response:**

```
{
    "__v": 0,
    "id": "5ebaa8a74cea0900186b7ec8",
    "price": 10,
    "title": "concert",
    "userId": "5ebaa6a3fc342b0023ded8a4"
}
```

<br/>

```
// GET ALL TICKET
$ curl \
--insecure \
--header "Content-Type: application/json" \
--request GET https://ticketing.dev/api/tickets/ \
| python -m json.tool
```

<br/>

```
// UPDATE TICKET
$ curl \
--insecure \
--cookie /tmp/cookies.txt \
--data '{"title":"new concert", "price":100}' \
--header "Content-Type: application/json" \
--request PUT https://ticketing.dev/api/tickets/5ebaa8a74cea0900186b7ec8 \
| python -m json.tool
``` -->

<br/>

---

<br/>

**Marley**

Any questions in english: <a href="https://jsdev.org/chat/">Telegram Chat</a>  
Любые вопросы на русском: <a href="https://jsdev.ru/chat/">Телеграм чат</a>