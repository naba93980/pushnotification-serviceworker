### Push Notification Service Worker

A small JavaScript project demonstrating browser push notification subscriptions using a Service Worker and a local Node.js server.

#### Flow

1. The browser registers `serviceWorker.js`.
2. `client.js` creates a push subscription and sends it to the server through `/subscribe`.
3. `index.js` handles the request using the server-side service logic.


#### Getting Started

**Prerequisites:** Node.js and npm, plus a browser that supports Service Workers and Push API.

1. Clone the repository:

   ```bash
   git clone https://github.com/naba93980/pushnotification-serviceworker.git
   cd pushnotification-serviceworker
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the local server using the script defined in `package.json`:

   ```bash
   npm start
   ```

4. Open the client page through the local server or a suitable local development server. Service Workers require a secure context, such as `localhost`; opening the HTML file directly may not work as expected.

5. Allow notification permissions when prompted and test the subscription flow.


#### Project Structure

- `client/` — HTML page, client-side JavaScript, and Service Worker
- `index.js` — Node.js server
- `package.json` — project dependencies and scripts
  

**Goal:** Understand how Service Workers and a Node.js backend work together to set up browser push notification subscriptions.
