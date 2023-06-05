# HouseBlend

Coffee shops to housing for all

## Project Overview

Lets make a map that has some sort of graph that shows housing prices based on the coffee shops around it.

## Project Goals

- Testing with Jest/Cypress
- Establish CI/CD pipeline
- Swap their FE over to Svelte hehe
- Switch over to Prisma
- Port Backend over to TS
- Deploy it

## Folder Structure

```bash
.
├── index.html
├── LICENSE
├── package.json
├── pnpm-lock.yaml
├── postcss.config.cjs
├── public
│   └── vite.svg
├── README.md
├── server
│   ├── controllers
│   │   ├── authController.ts
│   │   ├── censusController.js
│   │   ├── coffeeShopController.js
│   │   ├── dbController.js
│   │   ├── houseBlender.js
│   │   └── houseController.js
│   ├── models
│   │   ├── houseBlendCreate.sql
│   │   └── houseBlendModel.cjs
│   └── server.js
├── src
│   ├── App.tsx
│   ├── assets
│   │   ├── Coffee.png
│   │   ├── CoffeeWood.jpeg
│   │   ├── houseBlendLogo.png
│   │   ├── iced.png
│   │   ├── lukewarm.png
│   │   ├── piping.png
│   │   ├── react.svg
│   │   └── TaglineMain.png
│   ├── components
│   │   ├── article.tsx
│   │   ├── background.tsx
│   │   └── header.tsx
│   ├── main.tsx
│   ├── searchbar.tsx
│   ├── slider.tsx
│   ├── styles
│   │   └── index.css
│   └── vite-env.d.ts
├── tailwind.config.js
├── __testing__
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```
