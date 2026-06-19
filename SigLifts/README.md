# Group-Ideas---Creative-Space
Gym Rank Lifting App Fullstack.

SigLifts-project/
├── client/                 # Your React frontend
│   ├── src/
│   │   ├── components/     # UI pieces (Navbar, LiftCard, LogForm)
│   │   ├── pages/          # The main screens (Login, Dashboard, Leaderboard)
│   │   ├── api.js          # Single file for all backend fetch calls
│   │   └── App.js
├── server/                 # Your Node/Express backend
│   ├── routes/             # API endpoints (auth.js, workouts.js)
│   ├── models/             # Database schemas (User.js, Workout.js)
│   ├── dsa/                # The "Marks-getter" folder
│   │   └── heap.js         # Implementation of your Priority Queue
│   │   └── ranker.js       # Sorting & Percentile logic
│   ├── server.js           # Entry point (the heart of the backend)
│   └── .env                # Database credentials (KEEP PRIVATE)
├── .gitignore              # Crucial: ignore node_modules and .env
└── README.md               # How to run: "npm install", "npm start"
