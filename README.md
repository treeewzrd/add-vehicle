# Vehicle Manager

![Status](https://img.shields.io/badge/status-coursework-blue)
[![License: MIT](https://img.shields.io/badge/license-MIT-green)](LICENSE)

TypeScript coursework exploring inheritance and interfaces through an interactive vehicle CLI.

**Built with:** TypeScript, Node.js, Inquirer.

Create cars, trucks, and motorbikes, then choose vehicle actions from the menu.

## What I built

- Built interactive vehicle creation and action menus.
- Modeled cars, trucks, and motorbikes with shared behavior and specialized actions.
- Used TypeScript interfaces for driving and towing capabilities.

## Explore the source

- [src/classes/Cli.ts](src/classes/Cli.ts) — Interactive menus.
- [src/classes/Vehicle.ts](src/classes/Vehicle.ts) — Shared vehicle model.
- [src/classes/Truck.ts](src/classes/Truck.ts) — Truck behavior.
- [src/interfaces/AbleToTow.ts](src/interfaces/AbleToTow.ts) — Towing interface.

## Run locally

Requires Node.js/npm. From the repository root:

```bash
npm ci
npm start
```

`npm start` compiles TypeScript before launching `dist/index.js`. To compile without launching, use `npm run build`.

`npm test` is a placeholder. Check vehicle creation and menu actions manually.

Setup instructions were checked against source; builds and application behavior have not been rerun during this cleanup.

**License:** [MIT](LICENSE).
