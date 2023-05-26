# cm assessment

This assessment contains a simplified version of our monorepo, including a frontend and a backend application.

## Pre conditions

- Node.js should be installed.
- Clone recursivley: `git clone --recurse-submodules https://github.com/f4bio/cm-assessment.git`

## frontend
- The frontend application can be found at `apps/frontend`.
- Run `npm install` to install dependencies.
- Start the application with `npm run dev` for automatic updates.
- The server will listen on port 8080 or a free port.
- Source code is located in `apps/frontend/src`.
- The start page is defined under `apps/frontend/App.svelte`.

| Command        | Description                                                       |
|----------------|-------------------------------------------------------------------|
| `npm install` | Install all dependencies.                                          |
| `npm run build`   | Build the application.                                         |
| `npm start`   | Start the application (application must be built already).         |
| `npm run dev`     | Watch source code, rebuild, and execute package on change.     |

## api
- The API can be found at `apps/api`.
- Run `npm install` to install dependencies.
- Start the application with `npm run dev` for automatic updates.
- The server will listen on port 3000.
- Source code is located in `apps/api/src`.
- The REST controller is defined under `apps/api/src/UserRestController.ts`.

| Command        | Description                                                       |
|----------------|-------------------------------------------------------------------|
| `npm install` | Install all dependencies.                                          |
| `npm run build`   | Build the application.                                         |
| `npm start`   | Start the application (application must be built already).         |
| `npm run dev`     | Watch source code, rebuild, and execute package on change.     |
