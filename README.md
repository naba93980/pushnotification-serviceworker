### Push Notification Service Worker

A small JavaScript project demonstrating browser push notification subscriptions using a Service Worker and a local Node.js server.

#### Flow

1. The browser registers `serviceWorker.js`.
2. `client.js` creates a push subscription and sends it to the server through `/subscribe`.
3. `index.js` handles the request using the server-side service logic.

#### Project Structure

- `client/` — HTML page, client-side JavaScript, and Service Worker
- `index.js` — Node.js server
- `package.json` — project dependencies and scripts

**Goal:** Understand how Service Workers and a Node.js backend work together to set up browser push notification subscriptions.
