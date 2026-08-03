# 🎾 MatchPoint

MatchPoint is a modern full-stack web application built to help tennis players track their match history, analyze performance, and monitor long-term improvement.

Users can securely create an account, log matches, view detailed statistics, and review previous performances through an intuitive dashboard.

---

## Features

### 🔐 Authentication
- Secure user registration and login
- Individual user accounts
- Protected routes
- Session persistence using Supabase Authentication

### 🎾 Match Management
- Create new matches
- Edit existing matches
- Delete matches
- Record:
  - Opponent
  - Match Date
  - Singles or Doubles
  - Win / Loss
  - Match Score
  - Match Duration
  - Match Notes

### 📊 Statistics Dashboard

Automatically calculates:

- Total Matches
- Wins
- Losses
- Win Percentage
- Longest Winning Streak
- Total Sets Won
- Best Win % vs Opponent
- Average Match Duration

### 📝 Match Notes

Each match includes optional notes where players can record:

- Strengths
- Weaknesses
- Tactical observations
- Mental notes
- Areas for improvement

---

## Tech Stack

### Frontend
- React
- TypeScript
- Tailwind CSS
- Shadcn UI
- Vite

### Backend
- Supabase
- PostgreSQL
- Supabase Authentication

---

## Screenshots

### Login

(Add screenshot)

### Dashboard

(Add screenshot)

### Match Entry

(Add screenshot)

---

## Future Improvements

Planned features include:

- Match filtering
- Search by opponent
- Surface tracking (Hard, Clay, Grass)
- Tournament tracking
- Elo rating system
- Serve statistics
- Forehand / Backhand analytics
- Head-to-head history
- Charts and graphs
- CSV export
- Mobile optimization

---

## Getting Started

Clone the repository

```bash
git clone https://github.com/JoeyLiu518/MatchPoint.git
```

Install dependencies

```bash
npm install
```

Create a `.env` file using your own Supabase project credentials.

Start the development server

```bash
npm run dev
```

---

## Project Goals

This project was built to strengthen my experience with modern web development while solving a real-world problem I personally encounter as a competitive tennis player.

The application demonstrates experience with:

- Authentication
- CRUD operations
- Relational databases
- Responsive UI design
- TypeScript
- API integration
- State management
- User-specific data security

---

## Author

**Joey Liu**

GitHub:
https://github.com/JoeyLiu518

---

## License

This project is intended for educational and portfolio purposes.
