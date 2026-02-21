# FleetFlow Logistics Dashboard
FleetFlow is a modern fleet management dashboard for logistics companies, designed to streamline vehicle, driver, trip, and maintenance operations. This project features a responsive web interface, real-time search, analytics, and role-based access for managers and dispatchers.
## Features
- **Dashboard**: Command Center with live asset monitor, search by Vehicle ID or License Plate, and real-time filtering.
- **Registry**: Complete vehicle registry sourced from `vehicles.json`, with search and filter capabilities.
- **Analytics**: KPI cards, charts, and leaderboards for operational insights.
- **Safety & Maintenance**: Track maintenance costs, schedules, and safety compliance.
- **Theming**: Light and dark mode support with accessible, non-overlapping UI.
- **Currency**: All costs displayed in Rs.

## Project Structure
```
index.html
assets/
components/
  analytics.html
  dashboard.html
  dispatcher.html
  drivers.html
  registry.html
  safety.html
  sidebar.html
css/
  main.css
data/
  drivers.json
  maintenance.json
  trips.json
  vehicles.json
js/
  analytics.js
  app.js
  auth.js
  finance.js
  registry.js
  validation.js
```

## Getting Started
1. **Install dependencies**
   ```
   npm install
   ```
2. **Start the backend server**
   ```
   npm start
   ```
3. **Open `index.html` in your browser**

## Data Sources
- All data is stored in the `data/` folder as JSON files.
- Backend API serves data from these files (or SQLite if available).

## Customization
- Update CSS in `css/main.css` for theming.
- Add or edit components in `components/`.
- Update data in `data/` as needed.

## Credits
Developed by [Het and Zarvin Patel].

---
For issues or contributions, please open an issue or pull request.
video link:-
https://drive.google.com/drive/folders/1Gm9mHK5-fuqcRax4VRauI382aGebNS_q?usp=sharing
