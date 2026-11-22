# Campus Connect — readable code edition

This edition keeps the same app files and Firebase configuration, but formats the HTML, CSS, and JavaScript across multiple lines so you can study it.

## Run locally
1. Open this folder in VS Code.
2. Confirm Firebase Authentication has Email/Password enabled.
3. Confirm your Firestore database exists and publish the rules in `firestore.rules`.
4. Install the VS Code **Live Server** extension.
5. Right-click `index.html` and choose **Open with Live Server**.

## Study order
1. `js/firebase.js` — connects the app to Firebase.
2. `register.html` and `js/auth.js` — registration and login.
3. `chat.html` and `js/chat.js` — real-time messaging.
4. `firestore.rules` — database access rules.
5. `posts.html` / `js/posts.js`, then profile and reports.

Note: Formatting improves readability but does not itself change the app's feature completeness or security. The current role-field admin design is suitable only as a learning prototype; a production system should assign admin privileges through a trusted backend/custom claims.
