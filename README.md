# ScoreCast Frontend

A modern React + Vite frontend for the **ScoreCast** application. It provides a real-time sports dashboard by fetching match data through REST APIs and receiving live updates via WebSockets.

---

## Features

- Real-time sports score updates
- Live WebSocket integration
- Responsive user interface
- REST API integration
- Built with React, TypeScript, and Vite

---

## Tech Stack

- React
- TypeScript
- Vite
- WebSocket API
- Fetch API

---

## Project Structure

```text
scorecast/
├── components/
├── hooks/
├── services/
├── App.tsx
├── index.tsx
└── constants.ts
└── types.ts

```

---

## Prerequisites

- Node.js (v18 or later)
- npm

---

## Environment Variables

Create a `.env` file in the project root.

### Development

```env
VITE_API_BASE_URL=http://localhost:8000
VITE_WS_BASE_URL=ws://localhost:8000/ws
```

### Production

```env
VITE_API_BASE_URL=https://your-backend-url
```

---

## Running the Application

Start the development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Preview the production build:

```bash
npm run preview
```

---

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Starts the development server |
| `npm run build` | Builds the application |
| `npm run preview` | Previews the production build |
| `npm run lint` | Runs ESLint |

---

## Backend

Ensure the backend server is running before starting the frontend.
