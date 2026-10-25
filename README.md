# MindScape — CBT & Mood Reflection Toolkit

A single-page, browser-based demonstration of mood check-ins, CBT-style thought reflection, behavioral activation prompts, breathing pacing, and sensory grounding.

> **Educational self-help demo only.** MindScape is not a medical device or a clinically validated service. It does not diagnose, treat, or replace advice from a qualified mental-health professional. Stop any activity that feels uncomfortable. If you may be in immediate danger, contact local emergency services.

## Features

- **Mood check-ins:** Record mood, energy, emotion, context, and an optional note; review entries in a chart and export mood logs as CSV.
- **Thought records:** Reflect on an event, automatic thought, evidence, and a balanced alternative, with before-and-after distress ratings.
- **Behavioral activation:** Browse small suggested activities by broad state and track completion.
- **Breathing and grounding:** Use an optional visual breathing pacer with pause/resume and a 5-4-3-2-1 sensory checklist.
- **Data controls:** Export all app state as JSON or clear data saved by this app in the current browser.
- **Crisis-support links:** Find selected regional phone/text contacts in the app; availability and eligibility depend on location.

## Run it

Open `mindscape_evidence_based_mental_health_cbt_toolkit.html` in a modern browser. For a local HTTP preview, open PowerShell in this folder and run:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000/mindscape_evidence_based_mental_health_cbt_toolkit.html>. Stop the server with `Ctrl+C`.

The page loads Tailwind CSS and Chart.js from public CDNs, so an internet connection is needed for the full styling and chart. The app does not require a backend or account.

When opened with a clean browser profile, the app starts with sample mood check-ins and thought records so the chart and examples are populated. These are demo entries, not a clinical assessment. Clear or replace them before using the app for your own tracking.

## Privacy

- App state is stored in the browser's `localStorage` for this page's origin. It is not encrypted by the app and is not synchronized between browsers.
- Anyone using the same browser profile may be able to access this data. Avoid entering names, contact details, or other identifying or highly sensitive information.
- The page loads third-party JavaScript from Tailwind and Chart.js CDNs. Those scripts execute in the page; only use the demo if you are comfortable with those dependencies.
- **Export All Data (JSON)** downloads a copy of the stored state. **Clear Saved Data** removes this app's saved state from the current browser after confirmation. Clearing browser data or using another browser/profile can also affect stored entries.

## Crisis support

The support links in the page are not a substitute for local emergency services. Phone numbers, hours, eligibility, and text availability may change. If a number is unavailable or you are outside its service area, use local emergency services or a current regional helpline directory.

## Project contents

- `mindscape_evidence_based_mental_health_cbt_toolkit.html` — the complete standalone demo.

## License

No license is currently provided. All rights remain with the applicable copyright holder. Add a license only if you have the rights and intend to grant reuse permissions.
