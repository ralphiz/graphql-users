## Learning GraphQL

#### Run
1. `npm install`
2. `node server.js`
3. http://localhost:4000/graphql

#### Query Example
```
{
  user(id: "1") {
    id,
    firstName,
    age
  }
}
```