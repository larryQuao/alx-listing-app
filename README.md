# ALX Listing App

Implementing and creating a front-end clone of an AirBnB list page in both mobile and desktop view.

## Structure of the project

```
alx-listing-app/
├── components/
│   └── common/
│       ├── Button.tsx
│       └── Card.tsx
├── constants/
│   └── index.ts
├── interfaces/
│   └── index.ts
├── pages/
│   ├── _app.tsx
│   ├── _document.tsx
│   ├── api/
│   │   └── hello.ts
│   └── index.tsx
├── public/
│   └── assets/
│       ├── favicon.ico
│       ├── file.svg
│       ├── globe.svg
│       ├── next.svg
│       ├── vercel.svg
│       └── window.svg
├── styles/
│   └── globals.css
├── .
├── eslint.config.mjs
├── next-env.d.ts
├── next.config.ts
├── package.json
├── postcss.config.mjs
├── README.md
├── tailwind.config.js
└── tsconfig.json
```
### The `components` directory
Contains reusable React UI components used across the app. Keep small, focused building blocks (for example `Button`, `Card`, `Avatar`) in `components/common` and group larger feature or layout components in their own subfolders. Co-locate styles and tests with each component and prefer composition over duplication.

### The `constants` directory
Holds application-wide constants, enums, and configuration values (e.g., API endpoints, feature flags, magic numbers, static strings). Export values from `index.ts` and reference them throughout the codebase to avoid hard-coded literals.

### The `interfaces` directory
Stores TypeScript types and interfaces shared across the project: component props, API response shapes, and domain models. Keep types specific and re-export common/shared types from `index.ts` for easy imports.

### The `public/assets` directory
Contains static assets served by the app: images, icons, fonts, and other static files placed under `public/assets`. In Next.js these files are served statically (for example `/assets/favicon.ico`) and should be cacheable and immutable where possible. Store favicons, SVG icons, and other shared media here and reference them from components using absolute paths.

# Running ALX Listing App Locally

## Prerequisites
Before running a ALX listing application, ensure your have the following installed:
- Node.js (version 18.17 or later)
- npm, yarn, pmpn package manager

## Step-by-Step Guide

1. ### Clone or Download ALX listing app
    ``` bash
    git clone https://github.com/larryQuao/alx-listing-app.git
    cd alx-listing-app
    ```
2. ### Install Dependencies
    ```
    # Using npm
    npm install or npm i

    # Using yarn
    yarn install

    # Using pnpm
    pnpm install

    # Using bun
    bun install
    ```
3. ### Run the Development Server
    ```
    # Using npm
    npm run dev

    # Using yarn
    yarn dev

    # Using pnpm
    pnpm dev

    # Using bun
    bun run dev
    ```
4. ### Access the application
    Open your browser and navigate to:

    ```
    htttp://localhost:3000
    ```

