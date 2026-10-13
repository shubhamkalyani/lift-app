# Lift — Simple Workout App

This version is intentionally simple.

Navigation:
Home → Program → Day → Exercise

Programs included:
1. Normal Program
2. No-Legs Program
3. Leg Recovery Program

The app does NOT track weights or reps. Keep using Iron for that.

## Install on iPhone

For the full app-like / offline experience, the folder needs to be served over HTTPS.

Easy free option:
1. Unzip this file.
2. Create a GitHub repository.
3. Upload the contents of the `lift_simple_app` folder to the repo root.
4. Go to Settings → Pages.
5. Choose Deploy from a branch → main → root.
6. Open the GitHub Pages URL in Safari on your iPhone.
7. Tap Share → Add to Home Screen.

After opening it once, the app shell is cached for offline use.

## Editing workouts

All workout content lives near the top of `app.js` inside the `PROGRAMS` object.
