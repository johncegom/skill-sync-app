# 📘 Project: SkillSync – A Role-Based Learning Tracker (JT → ST Progressive Build)

A progressive learning-focused React project designed to help you **grow from JT to ST level** by incrementally applying frontend and JavaScript knowledge.

---

## 🔰 Phase 1: JT Level – Foundation Build

### 🎯 Goal

Build a clean, functional skill tracker UI using core HTML/CSS, basic JS, and foundational React.

### 🛠️ Features (Expanded)

- Display a list of skills (e.g., HTML, CSS, JavaScript)
- Each skill has a toggle (completed / in progress)
- `useState` for local state management
- Store skill state in `localStorage`
- Use **semantic HTML** (`section`, `ul`, `li`, `button`, `form`)
- Use **basic JSX** and React event handlers (`onClick`, `onChange`)
- Apply **CSS Modules / Tailwind** for layout and styling
- Support **keyboard navigation** and focus styles (A11Y basics)
- Show basic console logs (JT-level logging)
- Apply the **CSS box model**, flex layout, basic selectors
- Add simple unit tests for state toggle logic (optional)

### 📦 Tech Stack

- React + Vite
- TypeScript
- Tailwind CSS / CSS Modules
- Web Storage API
- Simple Unit Test: Vitest or Jest

### ✅ Skills Applied

- `useState`, `onClick`, JSX
- Variables, data types, arrays
- DOM events, localStorage
- Console logs
- Box model, flex basics
- Keyboard accessibility
- Semantic HTML

---

## ⚙️ Phase 2: TL Level – Dynamic UX + Data Logic

### 🎯 Goal

Enhance SkillSync with categories, routing, and async logic using core patterns.

### 🛠️ Features (Expanded)

- Skill categories (Frontend, Backend, UI/UX)
- Add/edit/remove skills
- Filter by category (`map`, `filter`, `sort`)
- Simulate fetching skills with `Promise`, `setTimeout`
- Responsive layout + media queries
- Handle async states: loading, error, data
- Lifting state up + `useEffect`
- Add dynamic routing: `/`, `/skill/:id` using React Router
- Form validation and error feedback
- Use `useRef`, `useCallback`, `useMemo` where needed
- Apply `strict equality`, scope rules, and `undefined/null` handling
- Implement **pseudo-classes**, transitions, and specificity awareness
- Style semantic elements + build for SEO

### 📦 Tech Stack

- React Router, SCSS, Tailwind
- Async JS logic: Promises
- Form handling libraries (e.g., Zod or basic JS validation)
- File structure with separation of components/hooks/utils

### ✅ Skills Applied

- Async logic (Promises)
- Array methods, anonymous functions
- Lifting state, conditional rendering
- useMemo, useCallback, useEffect
- Form handling, validation
- Flexbox + responsive layout
- Module scoping
- Web Fetch API (simulated)
- CSS pseudo-classes, transitions
- Equality checks and error objects

---

## 🧠 Phase 3: ST Level – Architecture, Optimization & Patterns

### 🎯 Goal

Scale app to use full architectural practices: global state, context, factory pattern, custom hooks, and dashboard analytics.

### 🛠️ Features (Expanded)

- Global theme and user role context (`admin` vs `user`)
- Manage skills via `useReducer` (supports undo/redo)
- Add custom hooks: `useLocalStorage`, `useShortcut`, `useTheme`
- Role-based dashboard routing (admin/user)
- Use **Factory Pattern** for rendering skill blocks
- Add charts (Chart.js or SVG-based) for skill completion stats
- Lazy load skill components
- Add performance optimizations: `defer`, `lazy`, `memo`
- Add **unit tests for reducers, hooks**, and state logic
- Advanced CSS: Grid, rem/vh units, transitions
- Use Logger (e.g., `console.group`, or `winston` for future backend)
- Apply `arrow functions`, closures, high-order functions
- Add `ECMAScript modules` with `import/export`
- Use semantic animation transitions
- Add fallback UIs and error boundaries

### 📦 Tech Stack

- React Context API
- `useReducer` + custom middleware/logger
- Tailwind + SCSS Grid layouts
- Chart.js or Recharts
- Jest + React Testing Library
- Role-based routes

### ✅ Skills Applied

- Context API, useReducer
- Closures, arrow functions, HOFs
- Custom hooks
- ECMAScript modules
- Lazy loading, performance optimization
- Logger setup (optional)
- Grid + advanced CSS units
- Responsive charts and data dashboards
- Factory and singleton pattern application

---

## 🧪 Bonus: Testing Foundation (Optional ST Bonus)

- React Testing Library setup
- Unit test for reducer logic
- Mock test for localStorage interaction
- RTL test for toggling skills

---

## ✅ Summary & Growth Path

| Phase | Goal                 | Key Concepts                       |
| ----- | -------------------- | ---------------------------------- |
| JT    | Functional UI        | Basic HTML/CSS, `useState`, events |
| TL    | Dynamic UX           | Async logic, performance, routing  |
| ST    | Architecture & State | Reducers, Context, Design Patterns |

---

## 📥 Tips

- Use Git branches to manage each phase: `phase/jt`, `phase/tl`, `phase/st`
- Document key learnings at each stage
- Keep commit messages focused on concepts
