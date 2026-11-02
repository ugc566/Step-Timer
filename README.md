# Time Steps – Offline Virtual Step Counter

Phone stays on the table; the app calculates steps from **elapsed time × steps per minute** (default 100/min).

- Start/Stop workout – steps saved automatically on stop
- Daily, Weekly, Monthly, Annual, All-time and Custom date-range views
- Progress ring/bar, bar-graph and calendar tick view (goal days get a ✓, streak shown)
- 100% offline: no internet, account, GPS or sensors. Data lives in the device's local storage
- Reliable timing: only the start timestamp is stored, so locking the screen or killing the app never loses time

## Publish on GitHub Pages and install on Android
1. Create a new repository and upload all files in this folder (keep them in the repo root).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `/ (root)` → Save.
3. Open `https://<your-username>.github.io/<repo>/` in Chrome on Android.
4. Chrome menu (⋮) → **Install app** / **Add to Home screen**. After the first load it works with no internet.

Tip: if a workout is running, leave the app alone; reopen it any time and the timer shows the true elapsed time.
