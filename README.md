# React + Redux + TypeScript Counter

A React application built with Vite, TypeScript, and Redux for practicing global state management.

## Technologies

- React
- TypeScript
- Vite
- Redux
- React Redux
- Redux Logger

## Features

- Increment the counter
- Decrement the counter
- Reset the counter
- Global state management using Redux
- Redux Logger middleware

## Project Structure

```text
src/
├── components/
│   ├── Counter.tsx
│   └── Counter.module.css
│
├── store/
│   ├── actions/
│   │   └── counterActions.ts
│   │
│   ├── reducers/
│   │   ├── counterReducer.ts
│   │   └── index.ts
│   │
│   └── store.ts
│
├── App.tsx
├── App.css
├── index.css
└── main.tsx
