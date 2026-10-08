# Daybook

A minimal journal and todo app with an Evernote-style layout, light/dark themes, and a fully responsive design. Built with React, TypeScript and Vite. All data stays in your browser (localStorage); there is no backend.

## Features

- **Journal**: entries with title, mood, tags, weather and location; drafts vs. published; favorites; search and filters by status, mood and tag.
- **Todos**: priorities, due dates, search, filters (status, priority, due), sorting, progress bar, and a distinct look for completed tasks.
- **Themes**: light, dark, or follow the system.
- **Responsive**: three-pane desktop layout, icon rail on tablets, bottom tab bar on phones.

## Getting started

Requires Node.js 20+.

```bash
npm install
npm run dev      # start the dev server at http://localhost:5173
npm run build    # type-check and build to dist/
npm run preview  # preview the production build
```

## Project structure

```
src/
  App.tsx            app shell, sidebar and routes
  pages/             Journal and Todos
  components/        EntryEditor, ThemeSwitch, Icons
  hooks/             useLocalStorage, useTheme
  types.ts           data models and migrations
  index.css          design tokens and styles
```
