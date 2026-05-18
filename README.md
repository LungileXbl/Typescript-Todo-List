# TypeScript Project - My List

A simple to-do list web app built with TypeScript and Vite.

## Features

- Add new list items
- Mark items as completed
- Remove individual items
- Clear all items
- Persist data in `localStorage`

## Tech Stack

- TypeScript
- Vite
- HTML/CSS

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Install

```bash
npm install
```

### Run in development

```bash
npm run dev
```

### Build for production

```bash
npm run build
```

### Preview production build

```bash
npm run preview
```

## Project Structure

```text
Typescript Project/
├── index.html
├── package.json
├── tsconfig.json
└── src/
	├── main.ts
	├── css/
	│   └── style.css
	├── modal/
	│   ├── FullList.ts
	│   └── ListItem.ts
	└── templates/
		└── ListTemplate.ts
```

## Notes

- List data is stored in browser storage under the key `myList`.
- The app initializes automatically when the DOM is loaded.
