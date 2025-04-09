# 📘 Project: SkillSync – A Role-Based Learning Tracker (JT → ST Progressive Build)

A progressive learning-focused React project designed to help you **grow from JT to ST level** by incrementally applying frontend and JavaScript knowledge.

---

## 🔰 Phase 1: JT Level – Foundation Build

### 🎯 Goal

Create a basic skill tracker UI with local state and layout using HTML, CSS, and basic React.

### 🛠️ Features

- Display a list of skills (e.g., HTML, CSS, JavaScript)
- Each skill has a toggle (completed / in progress)
- Use `useState` to manage status
- Save data to `localStorage`

### 📦 Tech Stack

- React + Vite
- TypeScript
- JSX, CSS Modules, Tailwind CSS, SCSS
- LocalStorage Web API

### ✅ Skills Applied

- Variable declarations, functions, arrays
- JSX, `useState`, events (`onClick`)
- Semantic HTML: `section`, `ul`, `li`
- CSS Box Model, Flexbox

---

## ⚙️ Phase 2: TL Level – Dynamic Logic & UX

### 🎯 Goal

Refactor the app to support multiple categories and introduce proper state patterns.

### 🛠️ Features

- Skill categories (Frontend, Backend, UI/UX)
- Add/edit/remove skills
- Filter by category
- Data fetching mock (simulate API with `Promise`)
- Responsive layout

### 📦 Tech Stack

- TypeScript
- `useEffect` + async data fetch simulation
- `useMemo`, `useCallback` for optimization
- React Router (basic routing: `/`, `/skill/:id`)
- SCSS, Tailwind CSS

### ✅ Skills Applied

- Function scope, anonymous functions
- Array methods: `map`, `filter`, `sort`
- Web Storage API
- React conditional rendering
- Responsive grid layout
- Flexbox + semantic HTML5

---

## 🧠 Phase 3: ST Level – Advanced State, Patterns & Optimization

### 🎯 Goal

Scale the app to support complex state flows, reusable components, and professional patterns.

### 🛠️ Features

- Global theme + user role context (admin vs user)
- `useReducer` to manage skill state tree
- Factory pattern for skill block rendering
- Custom hooks for localStorage, keyboard events
- Lazy rendering of skill cards
- Dashboard analytics with chart view (pie, progress)

### 📦 Tech Stack

- TypeScript
- React Context API
- Reducers and logger middleware
- Custom hooks: `useLocalStorage`, `useShortcut`
- Chart.js or SVG Pie Components
- Role-based routing (admin/user dashboard)
- SCSS, Tailwind CSS

### ✅ Skills Applied

- Closures, arrow functions, pure & HOFs
- Module, Singleton, Factory design patterns
- ECMAScript modules (`import/export`)
- CSS Grid, transitions, dynamic units (rem, vh)
- Testing prep: Unit tests for reducers and hooks

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
