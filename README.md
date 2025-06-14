# pinia-tasks

A simple Vue 3 + Pinia crash course project for managing tasks, demonstrating state management, actions, and integration with a mock REST API using json-server.

---

## Mock backend setup (json-server)

This project uses [`json-server`](https://github.com/typicode/json-server) to provide a mock REST API for tasks, using the `data/db.json` file.

### 1. Install json-server (if you haven't already)

```sh
npm install -g json-server
```
*Or use `npx` for a one-time run:*
```sh
npx json-server --watch data/db.json --port 3000
```

### 2. Start the mock backend

```sh
json-server --watch data/db.json --port 3000
```
- This will serve your tasks API at `http://localhost:3000/tasks`.

### 3. Start the frontend

In a separate terminal, run:

```sh
npm run dev
```
- This will start the Vite dev server (usually at `http://localhost:5173`).

### 4. Using the App

- The frontend will interact with the mock backend for all task operations (fetch, add, delete, etc.).
- Make sure **both** servers are running for full functionality.

---

## Project setup

The following commands are commonly used to set up and run this project:

- `npm install` – Installs all project dependencies listed in package.json.
- `npm run dev` – Starts the Vite development server with hot-reloading for local development.
- `npm run build` – Builds the app for production, outputting optimized static files to the `dist` directory.

