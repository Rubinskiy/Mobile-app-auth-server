# Mobile-app-auth-server

Let's say you want to register a user to a database, have them logged in to their accounts on request, or have them reset their account passwords because they forgot them. All from a mobile app.

First you have the client, which is the mobile app and the server, which is your app's API endpoint. The two are connected by requests.

```mermaid
graph LR
    A[Client] -->|Request| B[Server]
    B[Server] -->|JSON| A[Client]
```

In the graph above, the client requests the server for some information, and the server responds with the information encoded in the JSON format.

Now, let's be more specific and add a few details to this.

Now say you have a mobile app written in React Native that has only two functions:
- Login an existing user from the server's database
- Register a new user and add them to the server's database
