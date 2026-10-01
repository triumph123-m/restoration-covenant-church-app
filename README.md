# Restoration Covenant Church Worldwide - Mobile & Web App

A comprehensive church management and communication platform featuring a web admin dashboard, mobile app, and backend API.

## Project Structure

```
restoration-covenant-church-app/
├── backend/           # Node.js Express API
├── web/              # React Web Admin Dashboard
├── mobile/           # React Native Mobile App
└── docs/             # Documentation
```

## Features

- 📱 Mobile app for church members
- 🌐 Web dashboard for pastors/admins
- 📰 Announcements & news feed
- 📅 Event calendar
- ⛪ Church service schedules
- 🎥 Live stream integration
- 💰 Giving/donations
- 🙏 Prayer requests
- 📚 Sermon archives
- 👤 Admin authentication

## Tech Stack

- **Backend:** Node.js, Express, MongoDB
- **Web:** React, Redux, Material-UI
- **Mobile:** React Native, React Navigation
- **Database:** MongoDB
- **Authentication:** JWT

## Getting Started

### Prerequisites
- Node.js (v14+)
- npm or yarn
- MongoDB

### Installation

1. Clone the repository
```bash
git clone https://github.com/triumph123-m/restoration-covenant-church-app.git
cd restoration-covenant-church-app
```

2. Setup Backend
```bash
cd backend
npm install
npm run dev
```

3. Setup Web
```bash
cd ../web
npm install
npm start
```

4. Setup Mobile
```bash
cd ../mobile
npm install
npx react-native run-android  # or run-ios
```

## License

MIT License - See LICENSE file for details
