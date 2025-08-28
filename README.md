# Study Planner

A polished **Personalised Study Planner** to wow judges:
- AI-like auto scheduling (smart heuristic)
- Drag-and-drop weekly planner
- Subjects & deadlines
- Availability windows
- Progress charts
- LocalStorage persistence
- Smooth animations

## Tech
Vite + React + TailwindCSS + dnd-kit + Recharts + Framer Motion + lucide-react

## Run locally
```bash
# 1) Install dependencies
npm install

# 2) Start dev server
npm run dev
```

> If you're starting from scratch (optional): make sure Node 18+ is installed.

## Build
```bash
npm run build
npm run preview
```

## Notes
- The Auto-Plan button uses a greedy scheduler that fills your availability with subject blocks, prioritising difficulty, hours, and deadline proximity.
- All data is saved to localStorage so it survives refreshes.
- No backend required, great for demos.
