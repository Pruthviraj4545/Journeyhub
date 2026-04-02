# JourneyHub

Travel Agency management application built with Node.js, Express, and MongoDB.

## 📌 Project Overview
JourneyHub is a web-based system to:

- Create and browse travel packages
- Manage customer bookings
- View destination details
- Persist data in MongoDB
- Render UI via vanilla frontend under `public/`

## 🚀 Technologies
- Node.js
- Express
- MongoDB (native driver)
- HTML/CSS/JavaScript
- optional: nodemon (dev)

## 📁 Repository structure
- `server.js` - main backend server
- `public/` - static frontend:
  - `index.html`
  - `app.js`
  - `styles.css`
- `package.json` / `package-lock.json`
- `README.md`
- `.gitignore`

## ⚙️ Prerequisites
- Node.js 18+ installed
- npm
- MongoDB running locally (`mongodb://localhost:27017`) or Atlas cluster

## 🛠 Local setup
```bash
cd "C:\\Users\\Admin\\Desktop\\SEM VI\\FSDL\\Assignment5\\Journeyhub"
npm install
```

### Optional env file
Create `.env` in root if using custom URI:
```ini
MONGO_URI="mongodb://localhost:27017/journeyhub"
PORT=3000
```

## ▶️ Run
```bash
npm start
```

Development hot reload:
```bash
npx nodemon server.js
```

Then open: `http://localhost:3000`

## 🧪 Testing workflow
- Verify MongoDB launched and accepting connections
- Start server (`npm start`)
- Access UI and perform add/booking actions
- Confirm console prints `Connected to MongoDB` and `JourneyHub running` output

## 📦 Git workflow
```bash
git add .
git commit -m "Add JourneyHub project"
git push -u origin main
```

## 🌍 Deployment (basic)
1. Create repo: `https://github.com/Pruthviraj4545/Journeyhub`
2. Push local code
3. Deploy on platform (Heroku/Vercel/Render) using Node runtime

## 🏷 Tips
- Ensure `node_modules/` and `.env` are in `.gitignore`
- Keep `package-lock.json` for consistent installs

## 📝 License
MIT

