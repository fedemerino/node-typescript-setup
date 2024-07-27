# TypeScript Project with Node.js

This is a basic TypeScript/Node.js setup.

## Requirements

- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/fedemerino/node-typescript-setup.git
```

2. Navigate to the project directory:

```bash
cd node-typescript-setup
```

3. Install the dependencies.

```bash
npm install
```

## Scripts

- `npm run dev` Runs the application in development mode using `ts-node-dev`.
- `npm run start` Runs the application in production mode using `ts-node`.
- `npm run tsc` Compiles the TypeScript code to JavaScript.

## Project Structure

```plaintext
.
├── src
│   └── index.ts
├── package.json
├── tsconfig.json
└── README.md
```

## Usage

To run the application in development mode, use:

```bash
npm run dev
```

To compile the TypeScript code to JavaScript, use:

```bash
npm run tsc
```

To run the application in production mode, use:

```bash
npm run start
```