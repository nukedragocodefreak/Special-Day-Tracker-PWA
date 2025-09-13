# Special-Day-Tracker-PWA
# Special Moments – Event Tracker & Planner 🎉

A web-based Progressive Web App (PWA) to track, plan, and celebrate important events such as birthdays, anniversaries, and personal milestones.

This app helps users remember special dates, organize tasks, plan gifts or outings, and store memories — all in one intuitive interface.

Features (MVP)
1. Event Tracker & Countdown

- Add, edit, or delete events (birthdays, anniversaries, milestones).

- Countdown timer displaying days, hours, and minutes until each event.

- Responsive event cards with icons for different event types.

2. Gift Ideas List

- Curated gift suggestions based on the type of event.

- Ability to add custom gift ideas.

- Save favorite gifts per event for planning purposes.

3. Simple Planner / Reminders

- Task lists for each event (e.g., buy gift, book dinner).

- Mark tasks as complete with visual feedback.

- Optional reminders or notifications for upcoming tasks.

4. Memory Lane (Photos / Notes)

- Attach photos, videos, or text notes to each event.

- Display memories in a gallery or card view.

- Add/edit/delete notes for each memory.

## Tech Stack

- Frontend: React / Next.js

- Styling: Tailwind CSS

- State Management: React Context / Zustand / Redux

- PWA Support: Service Worker for offline usage and installable app

- Storage: LocalStorage or Firebase (for media and tasks)

- Deployment: Vercel / Netlify

```text
special-moments/
│
├── public/
│   ├── icons/                 # App icons for PWA
│   │   ├── icon-192x192.png
│   │   └── icon-512x512.png
│   ├── screenshots/           # Placeholder screenshots for README
│   │   ├── event-tracker.png
│   │   ├── countdown.png
│   │   ├── gift-ideas.png
│   │   └── memory-lane.png
│   └── manifest.json          # PWA manifest
│
├── src/
│   ├── components/            # React components
│   │   ├── EventCard.jsx
│   │   ├── CountdownTimer.jsx
│   │   ├── GiftList.jsx
│   │   ├── TaskPlanner.jsx
│   │   └── MemoryLane.jsx
│   ├── pages/                 # Next.js pages
│   │   ├── index.jsx
│   │   └── _app.jsx
│   ├── context/               # State management (React Context / Zustand)
│   ├── styles/                # Tailwind CSS / global styles
│   └── utils/                 # Helper functions
│
├── .gitignore
├── package.json
├── tailwind.config.js
├── postcss.config.js
├── README.md                  # Your polished README
└── next.config.js             # Next.js config (with PWA support)

