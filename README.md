# Fitgo - Deployment URLs

Fitness Tracker & Habit Planner. Firebase project: **fitgo-56029** (Spark plan).

## Live app
| What | URL |
|---|---|
| Live app (Firebase Hosting) | https://fitgo-56029.web.app |
| Alternate hosting address (default Firebase alias) | https://fitgo-56029.firebaseapp.com |

## Firebase console (owner: sapunno@gmail.com)
| What | URL |
|---|---|
| Project overview | https://console.firebase.google.com/u/0/project/fitgo-56029/overview |
| Authentication (users, sign-in methods) | https://console.firebase.google.com/project/fitgo-56029/authentication/users |
| Firestore database (saved data) | https://console.firebase.google.com/project/fitgo-56029/firestore |
| Hosting (deploy history) | https://console.firebase.google.com/project/fitgo-56029/hosting |

## Early preview (not the deployed app)
| What | URL |
|---|---|
| First prototype, "Forge" branding, saves to the browser only, not connected to Firebase | https://claude.ai/artifact/CPtzmRGJj1cMjykBQAgU7q |

## Notes
- The live app is `public/index.html`, deployed with `firebase deploy`.
- Data is stored in Firestore under `users/{uid}/habits`, `workouts` and `goals`, protected by `firestore.rules`.
- Only `fitgo-56029.web.app` was confirmed in the browser. The firebaseapp.com address and the console deep links follow Firebase's standard patterns; open them once to confirm.
- To redeploy after changes: `firebase deploy` from the project folder.
