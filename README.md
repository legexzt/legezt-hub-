# legexthub

Smart student notes, quiz, college community & admin management platform.

## Features
- Student notes upload/share (PDF/JPG/Handwriting)
- College search, enroll, my colleges list
- Quiz/test, doubt forum, community
- Location-based features (nearby colleges)
- Admin & Super Admin role system
- Approval workflows (admin, notes, colleges)
- Points, premium unlocks, leaderboard

## Tech Stack
- Frontend: ReactJS (`/client`)
- Backend: Node.js + Express (`/server`)
- Database: MongoDB Atlas (free)
- Auth: Firebase/Auth0 (free/student pack)
- Email: SendGrid (free)
- Hosting: Azure/Vercel (free)

## Project Structure
```
/client    # React frontend
/server    # Node backend
/mobile    # Android/iOS (future)
/docs      # Documentation
README.md  # Project guide
```

## Roles System
- **Super Admin:** All control (admins, settings, approvals)
- **Admin:** College, notes, user management (needs super admin approval)
- **Student/User:** Notes, quiz, enroll, forum, etc.

---

## Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/legexthub.git
cd legexthub
```

### 2. Setup folders
```bash
mkdir client server mobile docs
```

### 3. Start with `/client` and `/server` folder for web app.

---

## Contribution

- Keep code clean, commented, and push to main branch.
- Add docs for every major change.
- For queries, contact Super Admin.

---

## License

MIT
