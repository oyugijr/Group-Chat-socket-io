# Group Chat Client

This is the **client** for the Group Chat application, built with React, Vite, Tailwind CSS, and Socket.IO.

## Features

- Modern React UI for group chat
- Real-time messaging with Socket.IO
- User authentication and registration
- Responsive design with Tailwind CSS

## Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [pnpm](https://pnpm.io/) or [npm](https://www.npmjs.com/)

## Installation

1. **Navigate to the client directory:**

   ```sh
   cd client
   ```

2. **Install dependencies:**

   ```sh
   pnpm install
   ```

3. **Configure environment variables (optional):**

   If you need to set a custom API or Socket.IO server URL, create a `.env` file:

   ```sh
   touch .env
   echo "VITE_API_URL=http://localhost:5000" >> .env
   ```

## Running the Client

```sh
pnpm run dev
```

The app will be available at `http://localhost:5173` (or as shown in your terminal).

## Scripts

- `pnpm dev` – Start development server
- `pnpm build` – Build for production
- `pnpm preview` – Preview production build
- `pnpm lint` – Run ESLint

## Project Structure

```sh
client/
│
├── src/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   └── main.jsx
├── public/
├── tailwind.config.js
├── vite.config.js
└── ...
```

## Technologies Used

- React
- Vite
- Tailwind CSS
- Socket.IO Client
- Axios
- React Router

## License

MIT

---

*For the server, see the [`server/`](../server) directory.*
