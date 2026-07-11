# AALI OS

An operating-system-inspired interactive developer portfolio. Built to feel like a real OS — with a boot sequence, a windowed desktop environment, a terminal, and runnable "applications" — all running in the browser.

---

## Vision

Most developer portfolios are static pages. AALI OS is an experience.

The goal is to simulate a minimal operating system where visitors can:

- Boot into a custom shell
- Open applications (Projects, About, Contact, Skills)
- Run terminal commands to explore the portfolio
- Interact with a windowed desktop environment

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 16 (App Router) |
| UI | React 19 |
| Language | TypeScript 5 |
| Styling | Tailwind CSS v4 |
| Font | Geist Mono (via `next/font`) |

---

## Project Structure

```
aali-os/
├── app/              # Next.js App Router (routes + layouts)
├── components/       # Reusable UI components
├── core/             # OS core logic (window manager, process manager)
├── commands/         # Terminal command definitions
├── lib/              # Utility functions and helpers
├── types/            # Shared TypeScript types and interfaces
├── hooks/            # Custom React hooks
└── public/           # Static assets
```

---

## Roadmap

- [ ] Boot sequence / loading screen
- [ ] Desktop shell with taskbar
- [ ] Window manager (draggable, resizable windows)
- [ ] Built-in terminal with command parser
- [ ] Applications: Projects, About, Skills, Contact
- [ ] File system abstraction
- [ ] Theme / wallpaper support

---

## Getting Started

### Prerequisites

- Node.js 20+
- npm

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Lint

```bash
npm run lint
```

---

## License

MIT
