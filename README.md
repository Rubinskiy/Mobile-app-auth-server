# Mobile-app-auth-server

Let's say you want to register a user to a database, have them logged in to their accounts on request, or have them reset their account passwords because they forgot them. All from a mobile app.

First you have the client, which is the mobile app and the server, which is your app's API endpoint. The two are connected by requests.

```mermaid
graph LR
    A[Client] -->|Request| B[Server]
```
