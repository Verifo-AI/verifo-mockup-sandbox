# Verifo Mockup Sandbox

An internal design and component preview tool used while building the Verifo web app. It runs a Vite dev server that serves individual UI components in isolation, so design variants can be reviewed side by side before being merged into the main app.

## Stack

- React with Vite
- Tailwind CSS

## Requirements

- Node.js 18 or newer
- npm or pnpm

## Setup

1. Install dependencies:

   ```
   npm install
   ```

2. Start the dev server:

   ```
   PORT=5174 BASE_PATH=/ npm run dev
   ```

3. Open a component preview URL as configured in `mockupPreviewPlugin.ts`.

## Project layout

- `src/`, preview harness and component variants.
- `mockupPreviewPlugin.ts`, the Vite plugin that wires up per component preview routes.
