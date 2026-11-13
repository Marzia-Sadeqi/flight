# SkyRoute – Booking Flights from Kabul
React + Vite + Framer Motion + React Router.
## Run
npm install
npm run dev
## Build
npm run build
Project documents: open `public/docs/index.html` (or /docs/index.html when running). Videos: `public/videos`.
Deploy on Vercel: it detects Vite automatically. For page refresh on sub-pages add vercel.json (included).

## Videos
Four videos in `public/videos`: `skyN-p.mp4` (720x1280, phones) and `skyN-l.mp4` (1920x1080, desktop). `VBg` in `src/ui.jsx` picks the right file, pauses videos that are off-screen and respects "reduce motion".
