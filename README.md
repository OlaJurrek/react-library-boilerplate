# React Library Boilerplate

A minimal Vite-based boilerplate for TypeScript React libraries with hooks and utilities that don't require CSS.

## Features

- **TypeScript** — Full type safety with declaration files
- **Vite** — Fast builds and hot module replacement
- **ES Modules** — Outputs modern ES format
- **No CSS** — Pure TypeScript/JavaScript utilities
- **Tree-shakable** — Optimized for bundlers

## Installation

```bash
npm install
```

## Development

Start the development server:

```bash
npm run dev
```

## Building

Build the library for production:

```bash
npm run build
```

## Watch Mode

Rebuild on file changes:

```bash
npm run watch
```

## Publishing

```bash
npm publish
```

## Project Structure

```
src/
├── main.ts              # Entry point — exports all public APIs
├── hooks/
│   └── useIsMobile/     # Example of React hook for mobile detection
│       └── index.ts
└── utils/
    └── utilities.ts     # Example of a utility function
```

## Output

The build outputs:

- `dist/main.js` — ES module bundle
- `dist/main.d.ts` — TypeScript declarations

## License

MIT
