# Group Chat Server

This is the **server** for the Group Chat application built with Node.js, Express, MongoDB, and Socket.IO.

## Features

- Real-time group chat using Socket.IO
- RESTful API for user and message management
- MongoDB for data persistence
- CORS support for client-server communication

## Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)
- [pnpm](https://pnpm.io/) or [npm](https://www.npmjs.com/)

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/your-username/Group-Chat-socket-io.git
   cd Group-Chat-socket-io/server
   ```

2. **Install dependencies:**

   ```sh
   pnpm install
   # or
   npm install
   ```

3. **Configure environment variables:**

   Create a `.env` file in the `server` directory with the following content:

   ```sh
   PORT=5000
   MONGODB_URI=mongodb://localhost:27017/groupchat
   ```

   Adjust values as needed.

## Running the Server

```sh
pnpm start
# or
npm start
```

The server should now be running on `http://localhost:5000`.

## API Endpoints

- `POST /api/users` – Register a new user
- `POST /api/login` – User login
- `GET /api/messages` – Fetch chat messages
- `POST /api/messages` – Send a new message

## Socket.IO Events

- `connection` – When a client connects
- `chat message` – For sending/receiving messages in real-time
- `disconnect` – When a client disconnects

## Project Structure

```sh
server/
│
├── controllers/
├── models/
├── routes/
├── socket/
├── index.js
└── ...
```

## License

MIT

---

*For the client app, see the [`client/`](../client)
