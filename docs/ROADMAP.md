# 📘 SkillSync Learning Roadmap (JT → ST Progressive Build)

This document outlines each development phase in SkillSync aligned with **APAC JavaScript, React, and Layout/Design checklists**, built for structured, progressive learning.

---

## 🔰 Phase 1: JT Level – Foundation Build

### 🎯 Goal

Build a clean, functional skill tracker UI using core HTML/CSS, basic JS, and foundational React.

### 🛠️ Features

- Display a list of skills
- Toggle each skill (completed / in progress)
- Manage state with `useState`
- Save progress with `localStorage`
- Use semantic HTML tags: `section`, `ul`, `li`, `button`
- Basic JSX, `onClick`, `onChange`
- CSS styling using Tailwind or CSS Modules
- Add focus and keyboard navigation (basic A11Y)
- Console logs for debugging
- Unit test toggle logic (optional)

### ✅ Skills Applied

- React basics: JSX, `useState`, events
- DOM manipulation and localStorage
- HTML/CSS basics: box model, flex
- Semantic HTML, keyboard accessibility
- Console logging, basic testing knowledge

---

## ⚙️ Phase 2: TL Level – Dynamic UX + Data Logic

### 🎯 Goal

Introduce real-world state logic and routing through categories and async simulation.

### 🛠️ Features

- Skill categories: Frontend, Backend, UI/UX
- Add/edit/remove skill functionality
- Filter skills using `map`, `filter`, `sort`
- Simulate async fetch with Promises and delays
- Use `useEffect` to manage async lifecycle
- Dynamic routing: `/`, `/skill/:id`
- Form validation and error handling
- Use `useCallback`, `useRef`, `useMemo`
- Responsive layout (media queries)
- Apply pseudo-classes and transitions
- Implement equality logic, variable scoping
- Basic SEO practices via semantic tags

### ✅ Skills Applied

- Promises, async logic
- Functional patterns: anonymous functions, scoping
- React rendering logic: conditional rendering, `useEffect`
- Routing and URL parameters
- CSS transitions, media queries, pseudo-elements
- Form validation and async state management

---

## 🧠 Phase 3: ST Level – Architecture, Optimization & Patterns

### 🎯 Goal

Implement advanced architecture: global state, context, patterns, and performance enhancements.

### 🛠️ Features

- Global role/theme context (`admin`, `user`)
- Skill state via `useReducer` (with undo/redo)
- Custom hooks: `useLocalStorage`, `useShortcut`, `useTheme`
- Dashboard view with charts (progress, pie)
- Lazy rendering of skill components
- Factory pattern for skill UI rendering
- Add logger middleware to reducers
- Add fallback UIs and error boundaries
- Grid layout, rem/vh units, animations
- ECMAScript modules with `import/export`
- Arrow functions, closures, HOFs
- Unit testing: hooks, reducers, components

### ✅ Skills Applied

- Context API, reducers, custom hooks
- Architectural patterns: Factory, Singleton
- Performance: lazy loading, memoization
- Advanced styling: CSS Grid, units, transitions
- Testing with Jest + React Testing Library
- Logger setup (optional)

---

## 🧪 Bonus: Testing Foundation (Optional ST Bonus)

- React Testing Library setup
- Unit test reducer logic
- RTL test for skill toggling
- LocalStorage mock tests

---

## 🧭 Learning Path Summary

| Phase      | Level | Focus                            |
| ---------- | ----- | -------------------------------- |
| 🔰 Phase 1 | JT    | Basic HTML/CSS, useState, Events |
| ⚙️ Phase 2 | TL    | Async logic, Categories, Routing |
| 🧠 Phase 3 | ST    | Architecture, Reducers, Context  |

Use Git branches:

- `phase/jt` → Foundation
- `phase/tl` → Logic + UX
- `phase/st` → Architecture + Optimization
