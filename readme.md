# Request
A simple promise based and single file wrapper for newers to start using Fetch API.

For those who dont want a big library to simple requests, and yet want to simplify the fetch use.

[![npm version](https://badge.fury.io/js/%40schirrel%2Frequest.svg)](https://badge.fury.io/js/%40schirrel%2Frequest)

## Installing

Just import the `Request.js` file or run `npm i @schirrel/request`.

## Examples

See [Example Folder](https://github.com/schirrel/request/tree/master/docs)

#### GET

```javascript
Request.get("https://jsonplaceholder.typicode.com/todos/1")
.then((res) => {})
.catch((err) => {});

```
#### POST
```javascript
Request.post('https://jsonplaceholder.typipre.com/posts', {
    body: {
        title:'Ahoy'
    }
})
.then((res) => {})
.catch((err) => {});

```
#### PUT
```javascript
Request.put('https://jsonplaceholder.typicode.com/posts/1', {
body: {
   id:1,
   title:'Ahoy'
    }
 })
.then((res) => {})
.catch((err) => {});

```
#### DELETE
```javascript
Request.delete('https://jsonplaceholder.typicode.com/posts/1')
.then((res) => {})
.catch((err) => {});

```


For a http client you can also check [api-request](https://github.com/schirrel/api-request) current under development
