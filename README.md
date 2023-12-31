# Graphite take-home frontend repo

Thanks for deciding to interview with Graphite! This repository is meant to get you up and running with a TypeScript + React project, so you can start working on the actual interview problem from minute 1.

This repo was created with Vite, and comes with:

- React
- TypeScript
- eslint
- dev server + hot module reload

⚠️ Please do the entire **Setup** portion below _before_ you do the take-home interview. This will ensure that you don't spend any of your precious interview time on repo setup!

## Setup

Clone the repo:

```bash
git clone https://github.com/withgraphite/frontend-interview.git
```

Install the dependencies:

```bash
cd frontend-interview
npm install
```

### Make sure the server boots

Make sure the server boots by running:

```bash
cd frontend-interview
npm run dev
```

You should see output like:

```
  VITE v4.3.9  ready in 179 ms

  ➜  Local:   http://127.0.0.1:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help
```

Visit the `Local:` url given in the Vite output (http://127.0.0.1:5173/). You should see something like this:

![default app](https://github.com/withgraphite/frontend-interview/assets/59429/337cfdfb-0e6e-42cb-812b-c46b66c98173)

## Making frontend changes

To change the default app you see, open `src/App.tsx` and start making changes. The page should hot reload whenever you save a file.

## Linting

You can run eslint with `npm run lint`.

## Meta

This frontend repo was created with `npm create vite@latest -- --template react-ts`.

If you need more documentation on Vite for any reason, please [read their docs](https://vitejs.dev/guide/).
