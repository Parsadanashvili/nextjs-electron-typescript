
# Next.JS Electron App with Typescript

| Part       | Source code (Typescript) | Builds (JavaScript) |
| ---------- | ------------------------ | ------------------- |
| Next.js    | `/`                      | `/`                 |
| Electron   | `/electron-src`          | `/electron-build`   |
| Production |                          | `/dist`             |

## Available commands:

```bash
"build-next": build and transpile Next.js layer
"build-electron": transpile electron layer
"build": build both layers
"dev-next": start nextjs dev version
"dev-electron": start electron dev version
"dist": create production electron build
"start": start nextjs build version
"type-check": check TypeScript in project
```