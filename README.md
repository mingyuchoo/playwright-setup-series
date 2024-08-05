# playwright-setup-series

## Prerequisites

- node
- pnpm

## Getting Started

Create a node project

``` bash
mkdir <project-name>
cd <project-name>
```

### Installing Playwright using pnpm

`pnpm create playwright`

- Choose between TypeScript or JavaScript (default is TypeScript)
- Name of your Tests folder (default is tests or e2e if you already have a tests folder in your project)
- Add a GitHub Actions workflow to easily run tests on CI
- Install Playwright browsers (default is true)

### How to test with Playwright

Runs the end-to-end tests

`pnpm exec playwright test`

Starts the interactive UI mode

`pnpm exec playwright test --ui`

Runs the tests only on Desktop Chrome

`pnpm exec playwright test --project-chromium`

Runs the tests in a specific file

`pnpm exec playwright test example`

Runs the tests in debug mode

`pnpm exec playwright test --debug`

Auto generate tests with Codegen

`pnpm exec playwright codegen <URL>`

## References

- <https://playwright.dev/>
