# HostelOS — Hostel Management System

A responsive, browser-based hostel administration prototype built with HTML, CSS and vanilla JavaScript.

## Run in VS Code

1. Extract the ZIP file.
2. Open the `hostel-management-system` folder in VS Code.
3. Open `index.html` in a browser, or install the **Live Server** VS Code extension and choose **Open with Live Server**.
4. The first load seeds sample students, rooms, passes, attendance, events and alerts.

The app is designed to work without a build step. Google Fonts, Leaflet and OpenStreetMap tiles need internet access. The rest of the interface runs locally.

## Features

- Dashboard with dynamically calculated hostel statistics
- Student records: create, edit, view, search, deactivate, CSV export
- Room and bed capacity management
- Local, Main and Home pass types
- Pass approval, rejection, departure and return workflows
- Overdue return status and alert inbox
- Leaflet map view and clearly labelled simulated location updates
- Attendance by date and session, with CSV export
- Events and announcements
- Alerts acknowledgement/resolution
- Settings, JSON backup and demo-data reset
- Responsive desktop and mobile layout
- Browser `localStorage` persistence

## Important prototype limitations

- Data is stored in the current browser only. It is not shared with other wardens/devices.
- Sample data is fictitious. Do not enter real sensitive student information in a public/shared computer.
- Login, server-side permissions and multi-user access are not implemented.
- Map markers and location simulator are demonstrations, not live GPS tracking.
- Real tracking needs an authorized student-side app/site, explicit location permissions, a backend, server-side geofence checks and a retention/privacy policy.
- This is not production-ready for real hostel administration until secure authentication, backend validation, backups and access controls are added.

## Reset or back up

Open **Settings** to download a JSON backup or restore the original sample data. CSV export is available on the student, pass, attendance and events screens.

## Suggested next step

Add a Node.js/Express API and persistent database, then implement secure admin/student roles and an authorized student-side pass and location workflow.
