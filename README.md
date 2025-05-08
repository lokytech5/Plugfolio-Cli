# Plugfolio CLI

A command-line interface (CLI) tool for deploying applications to Plugfolio, a Platform as a Service (PaaS) that simplifies backend deployment.

## Installation

Install the CLI globally via npm:

```bash
npm install -g plugfolio-cli
```

## Development

### Prerequisites
- Node.js (>=18)
- npm

### Scripts
- `npm run build`: Compile TypeScript to JavaScript.
- `npm run start`: Run the compiled CLI.
- `npm run lint`: Lint the code with ESLint.
- `npm run format`: Format the code with Prettier.
- `npm run test`: Run unit tests with Jest.

### CI/CD
The project uses GitHub Actions for CI/CD:
- On every push/PR to `main`, it runs linting, testing, and building.
- On pushes to `main`, it publishes the CLI to npm (requires `NPM_TOKEN` in GitHub Secrets).