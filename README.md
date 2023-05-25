# Assessment

This assessment contains a simplified version of our monorepo, including a frontend and a backend application.

## Pre conditions

- Node.js v16.18.0 should be installed.

## frontend
- The frontend application can be found at `apps/frontend`.
- Run `yarn install` to install dependencies.
- Start the application with `yarn dev` for automatic updates.
- The server will listen on port 8080 or a free port.
- Source code is located in `apps/frontend/src`.
- The start page is defined under `apps/frontend/App.svelte`.

| Command        | Description                                                       |
|----------------|-------------------------------------------------------------------|
| `yarn install` | Install all dependencies.                                         |
| `yarn build`   | Build the application.                                            |
| `yarn start`   | Start the application (application must be built already).        |
| `yarn dev`     | Watch source code, rebuild, and execute package on change.        |

## api
- The API can be found at `apps/api`.
- Run `yarn install` to install dependencies.
- Start the application with `yarn dev` for automatic updates.
- The server will listen on port 3000.
- Source code is located in `apps/api/src`.
- The REST controller is defined under `apps/api/src/UserRestController.ts`.

| Command        | Description                                                       |
|----------------|-------------------------------------------------------------------|
| `yarn install` | Install all dependencies.                                         |
| `yarn build`   | Build the application.                                            |
| `yarn start`   | Start the application (application must be built already).        |
| `yarn dev`     | Watch source code, rebuild, and execute package on change.        |