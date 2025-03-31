# hello-vscode-github-copilot

A simple TypeScript project with Jest testing framework integration.

## Overview

This repository demonstrates a basic TypeScript setup with Jest for testing. It includes a simple `sum` function and corresponding unit tests.

## Project Structure

```
.
├── src/               # Source code
│   ├── index.ts       # Main source file with sum function
│   └── __tests__/     # Test directory
│       └── index.test.ts  # Tests for index.ts
├── jest.config.js     # Jest configuration
├── tsconfig.json      # TypeScript configuration
├── package.json       # Project dependencies and scripts
└── .gitignore         # Git ignore file
```

## Prerequisites

- Node.js (v22.14 or newer)
- npm (v10.9 or newer)

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/tamakiii-sandbox/hello-vscode-github-copilot.git
cd hello-vscode-github-copilot
npm install
```

## Available Scripts

In the project directory, you can run:

### `npm test`

Runs all tests using Jest.

### `npm run test:watch`

Runs tests in watch mode, which will automatically rerun tests when files change.

### `npm run build`

Compiles TypeScript code into JavaScript in the `dist/` directory.

## Features

- TypeScript for type safety
- Jest for unit testing
- Simple and clean project structure

## CI/CD

This project uses GitHub Actions for continuous integration. On every pull request and push to the main branch, the workflow will:

- Build the TypeScript code
- Run all tests
- Verify compatibility with Node.js versions 16, 18, and 20

The workflow configuration can be found in `.github/workflows/build-and-test.yml`.

## License

ISC