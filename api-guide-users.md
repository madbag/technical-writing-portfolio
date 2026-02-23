# JSONPlaceholder API - Users Endpoint Guide

## What is JSONPlaceholder?

JSONPlaceholder is a free, fake REST API used for testing and practice. It returns sample data - including user, posts and comments - without requiring any setup or authentication. 

It is commonly used by developers and technical writers to practice working with API responses. 

---

## The /users Endpoint

The `/users` endpoint returns a list of 10 fictional users. Each user includes the following information: 

- Name and username
- Email address
- Phone number
- Website
- Address
- Company name

---

## How to Make a Request

No setup is required. To retrieve the user list: 

1. Open your browser
2. Copy and paste the following URL into the address bar: 

`https://jsonplaceholder.typicode.com/users`

3. Press **Enter**

The response will appear immediately in your browser.

---

## What the Response Looks Like

The API returns data in JSON format. Here is an example of the first user returned:
```json
{
  "id": 1,
  "name": "Leanne Graham",
  "username": "Bret",
  "email": "Sincere@april.biz",
  "phone": "1-770-736-0860 x56442",
  "website": "hildegard.org"
}
```

[Screenshot: full browser response]
