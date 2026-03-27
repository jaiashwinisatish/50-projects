# 🚀 50 Projects in 50 Days Beginner's Visual Guide

> **HTML · CSS · JavaScript** | Learn by Building | No Frameworks Needed

---

## 🌟 What Is This?

A collection of **50 mini front-end projects** built using only HTML, CSS, and vanilla JavaScript.
Each project teaches one or two key concepts in a fun, hands-on way.

```
🧠 Learn a concept → 🏗️ Build a project → 💡 Understand how it works
```

---

## 🗺️ How This Repo Is Organized

Every project lives in its own folder with 3 files:

```
project-name/
├── index.html    ← Structure (what's on the page)
├── style.css     ← Appearance (how it looks)
└── script.js     ← Behavior (what it does)
```

---

## 🛠️ Tech Stack

```
┌─────────────────────────────────────┐
│           TECH STACK                │
├─────────────┬───────────┬───────────┤
│   HTML5     │   CSS3    │  JS (ES6) │
│  Structure  │  Styling  │  Logic    │
│  & Markup   │  & Anim.  │  & DOM    │
└─────────────┴───────────┴───────────┘
```

No React. No Vue. No TypeScript.
Just the **3 core languages of the web**  pure and simple.

---

## 📂 All 50 Projects at a Glance

### 🎨 Visual & Animation Projects

| # | Project | Key Concept |
|---|---------|-------------|
| 01 | 🃏 Expanding Cards | CSS Flexbox + transitions |
| 02 | 📦 3D Boxes Background | CSS transforms + grid |
| 03 | ⏳ Animated Countdown | CSS `@keyframes` + JS events |
| 04 | 🧭 Animated Navigation | CSS transitions + toggle |
| 05 | 🔄 Rotating Navigation | CSS `transform-origin` |
| 06 | 🔵 Button Ripple Effect | Dynamic DOM + animation |
| 07 | 🌀 Kinetic Loader | CSS pseudo-elements |
| 08 | 📜 Scroll Animation | `getBoundingClientRect()` |
| 09 | 🖼️ Background Slider | CSS background transitions |
| 10 | 🌫️ Blurry Loading | CSS `filter: blur()` |

### 🧩 UI Component Projects

| # | Project | Key Concept |
|---|---------|-------------|
| 11 | 🔍 Hidden Search | CSS width transition |
| 12 | ❓ FAQ Collapse | Toggle classes |
| 13 | 📋 Content Placeholder | CSS `@keyframes` shimmer |
| 14 | 📱 Mobile Tab Navigation | Active state management |
| 15 | 🍔 Netflix Navigation | Layered slide animation |
| 16 | 📣 Feedback UI | Event delegation |
| 17 | 🧾 Form Input Wave | `split('')` + `map()` |
| 18 | ✅ Verify Account UI | Input focus chaining |
| 19 | 🔔 Toast Notification | Dynamic element creation |
| 20 | 🗂️ Progress Steps | State tracking |

### 📊 Interactive Logic Projects

| # | Project | Key Concept |
|---|---------|-------------|
| 21 | 🧮 Incrementing Counter | `setTimeout` animation |
| 22 | 💧 Drink Water Tracker | DOM state management |
| 23 | 🎲 Random Choice Picker | Arrays + `setInterval` |
| 24 | 📝 Todo List | `localStorage` + CRUD |
| 25 | 📓 Notes App | `localStorage` + Markdown |
| 26 | 🔐 Password Generator | String + randomization |
| 27 | 🎯 Quiz App | Array data + scoring |
| 28 | 🤣 Dad Jokes | Fetch API + JSON |
| 29 | ⌨️ Event Keycodes | Keyboard event listeners |
| 30 | ✅ Good Cheap Fast | Constraint logic |

### 🖱️ DOM & Event Projects

| # | Project | Key Concept |
|---|---------|-------------|
| 31 | 🖱️ Drag N Drop | HTML5 Drag API |
| 32 | 🎨 Drawing App | Canvas API |
| 33 | ❤️ Double Click Heart | Custom double-click logic |
| 34 | 🎚️ Custom Range Slider | Input events + positioning |
| 35 | 📸 Random Image Feed | Dynamic `<img>` generation |
| 36 | 🐝 Hoverboard | MouseOver + CSS glow |
| 37 | 🌊 Split Landing Page | CSS clip + hover expand |
| 38 | 📌 Sticky Navigation | Scroll position detection |
| 39 | 🔤 Auto Text Effect | `slice()` + `setTimeout` |
| 40 | 🎠 Image Carousel | `translateX` + `setInterval` |

### 🌐 API / Advanced Projects

| # | Project | Key Concept |
|---|---------|-------------|
| 41 | 🐱 GitHub Profiles | Axios + GitHub API |
| 42 | 🎬 Movie App | TMDB API + search |
| 43 | 🧬 Pokedex | Pokémon API + loops |
| 44 | 🔄 Testimonial Switcher | `setInterval` + arrays |
| 45 | 🕐 Theme Clock | `Date()` + CSS vars |
| 46 | ⏱️ Simple Timer | Conic gradient + `setInterval` |
| 47 | 🔊 Sound Board | Audio API |
| 48 | 🪲 Insect Catch Game | Dynamic positions + score |
| 49 | 🔑 Password Strength BG | `filter: blur()` on input |
| 50 | 👤 Live User Filter | Fetch API + filter logic |

---

## 🔄 How a Typical Project Works

Here's a simplified flowchart for most projects in this repo:

```
        ┌─────────────────────┐
        │   User Opens Page   │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  HTML renders DOM   │
        │  CSS styles the UI  │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  JS selects elements│
        │  via querySelector  │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  Event Listener     │
        │  (click/scroll/key) │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  Function runs      │
        │  (logic + DOM edit) │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  UI updates visually│
        └─────────────────────┘
```

---

## 🧠 Core Concepts You'll Learn

### 📌 DOM Manipulation Flow

```
JavaScript → selects → HTML Elements
     │                      │
     └── reads/writes ───▶  │
                            ▼
                    Updates the Page
```

### 📌 CSS Animation Lifecycle

```
Initial State  ──▶  Trigger (hover/class/scroll)
                         │
                         ▼
               Transition / Keyframe plays
                         │
                         ▼
               Final State reached
                         │
               (optionally reverses)
```

### 📌 Fetch API (used in API projects)

```
JS: fetch(URL)
       │
       ▼
 HTTP Request sent to API server
       │
       ▼
 Server returns JSON response
       │
       ▼
 .json() parses the data
       │
       ▼
 DOM is updated with results
```

---

## ▶️ How to Run Any Project

### Option 1 — Open directly

```bash
# Clone the repo
git clone https://github.com/jaiashwinisatish/backend-projects.git

# Open any project
cd expanding-cards
# Then double-click index.html to open in browser
```

### Option 2 — Use Live Server (recommended)

```
1. Install VS Code
2. Install "Live Server" extension
3. Right-click index.html → "Open with Live Server"
4. Browser auto-refreshes on every save ✅
```

---

## 🧩 Beginner Learning Path

Start here if you're new to web development:

```
WEEK 1 — HTML & CSS Basics
   ├── expanding-cards        (flexbox)
   ├── progress-steps         (CSS variables)
   ├── hidden-search          (transitions)
   └── blurry-loading         (CSS filters)

WEEK 2 — JavaScript Fundamentals
   ├── event-keycodes         (keyboard events)
   ├── incrementing-counter   (setTimeout)
   ├── faq-collapse           (classList toggle)
   └── todo-list              (CRUD + localStorage)

WEEK 3 — DOM Projects
   ├── drawing-app            (Canvas API)
   ├── drag-n-drop            (Drag API)
   ├── image-carousel         (setInterval)
   └── quiz-app               (arrays + state)

WEEK 4 — APIs & Advanced
   ├── dad-jokes              (fetch API)
   ├── github-profiles        (Axios + real API)
   ├── movie-app              (search + API)
   └── pokedex                (loops + API)
```

---

## 💡 Key JavaScript Concepts Map

```
JavaScript Concepts Used in This Repo
│
├── 🔎 DOM Selection
│      querySelector / querySelectorAll / getElementById
│
├── ⚡ Events
│      click / keydown / scroll / mouseover / dragstart
│
├── ✏️ DOM Manipulation
│      innerHTML / classList / style / createElement
│
├── ⏱️ Timing
│      setTimeout / setInterval / clearInterval
│
├── 🌐 Fetch / Async
│      fetch() / async-await / .then() / .json()
│
├── 💾 Storage
│      localStorage.setItem / getItem / JSON.stringify
│
└── 🎨 Canvas
       getContext / arc / lineTo / fillStyle
```

---

## 🤝 Contributing

1. Fork this repository
2. Pick a project idea
3. Create your folder: `my-project/`
4. Add `index.html`, `style.css`, `script.js`
5. Open a pull request!

---

## 📄 License

MIT License — free to use, modify, and share.

---

<div align="center">

**Made with ❤️ for learners everywhere**

*Star ⭐ the repo if it helped you learn!*

</div>
