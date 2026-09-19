# FOCUSVERSE Analytics
Private analytics + website analyzer dashboard.

Upload this project to GitHub Pages. Firebase Authentication protects the dashboard.
GitHub Pages cannot bypass CORS, so arbitrary-site analysis is browser-limited; a server
proxy is required for unrestricted crawling.

Setup:
1. Create a Firebase Web App.
2. Enable Email/Password Authentication.
3. Create Firestore.
4. Put your Firebase config in firebase-config.js.
5. Put your admin email in firebase-config.js and firestore.rules.
6. Deploy to GitHub Pages.

Never put a Firebase service-account/private key in this repository.
