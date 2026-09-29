# Testing React State Arrays

A small React application for practicing state management, array updates, and
component testing with React Testing Library.

The app renders a list of items and provides controls to add a new item or
remove an existing item. It is intended as a focused course exercise for
learning how immutable array updates affect the UI.

## Learning goals

- Store an array in component state with `useState`.
- Add items without mutating the existing state.
- Remove items with `Array.prototype.filter`.
- Test rendered content and user interactions.

## Built with

- [React](https://react.dev/)
- [Create React App](https://create-react-app.dev/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Jest](https://jestjs.io/)

## Getting started

### Prerequisites

- [Node.js](https://nodejs.org/) and npm

### Installation

1. Clone the repository.
2. Change into the project directory.
3. Install dependencies:

   ```bash
   npm install
   ```

### Start the development server

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in a browser. The page
reloads automatically when source files change.

## Available scripts

| Command | Description |
| --- | --- |
| `npm start` | Start the development server. |
| `npm test` | Run the test suite in interactive watch mode. |
| `npm run build` | Create an optimized production build in `build/`. |
| `npm run eject` | Eject from Create React App configuration. This is irreversible. |

## Project structure

```text
src/
├── App.js          # Root component
├── TestCard.js     # Stateful item-list exercise
├── App.test.js     # Component tests
└── index.js        # Application entry point
```

## Testing

Run the test suite with:

```bash
npm test
```

Use the existing tests as a starting point for adding coverage around adding
and removing items.
