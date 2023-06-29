# Graphite take-home frontend repo

Thanks for deciding to interview with Graphite! This repository is meant to get you up and running with a TypeScript + React project, so you can start working on the actual interview problem from minute 1.

Please do the entire **Setup** portion below _before_ you do the take-home interview. This will ensure that you don't spend any of your precious interview time on repo setup!

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

![image](https://github.com/withgraphite/frontend-interview/assets/59429/5738bcaa-a700-4eef-8600-f3190b7e504f)

## Making frontend changes

To change the default app you see, open `src/App.tsx` and start making changes.

## Linting

You can run eslint with `npm run lint`.
