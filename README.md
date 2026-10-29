# Kreepy Todo

A compact React state-management exercise: add, edit, complete, and delete tasks.

[Open the demo](https://react-todo-list-onobrain.vercel.app) · [Browse the code](https://github.com/hamzaxbella/react-todo-list)

## What it demonstrates

Reusable forms, immutable array updates, conditional editing, and UUID-based task identifiers.

## Run locally

```bash
git clone https://github.com/hamzaxbella/react-todo-list.git
cd react-todo-list
npm ci
npm start
```

Open <http://localhost:3000> (or the address printed in the terminal).

```bash
npm run build
```

Use the build script to generate production output.

## Code map

`src/components/TodoWrapper.js` owns task state. `TodoForm.js` and `EditTodoForm.js` handle input; `Todo.js` renders a task and its actions.

This project uses Create React App. Tasks are held in React state and reset on refresh; there is no persistence, account system, or backend. It is retained as a learning project.
