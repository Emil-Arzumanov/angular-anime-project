# 2023 Internship
Monorepo with Angular, Vanilla TS solo projects from 2023 summer internship.
Created with [Nx](https://nx.dev/).
## Installation

`npm install` to install all required dependencies.

## Usage

### Development

Run command to start development server

```bash
npm run [project]:serve
```

### Build

Run command to build the application.

```bash
npm run [project]:build
```

### Linting

You can read about linting on the [wiki](https://wiki.saritasa.rocks/frontend/tools/linting/).

To manually run `eslint` over your code, you can perform command in the terminal.

```bash
npm run [project]:lint
```

To manually run `stylelint` over your code, you can perform command in the terminal.

```bash
npm run [project]:stylelint
```

## Workspace structure

Workspace consists of applications and libraries. A lib contains the actual logic that can be shared across the workspace. An application is an unit that link, bundle and compile functionality implemented in libraries for being deployed.

### Applications

- [Vanilla](apps/vanilla/README.md)
- [Angular](apps/angular/README.md)

### Libraries

- [Core](libs/core/README.md)
- [Theme](libs/theme/README.md)
