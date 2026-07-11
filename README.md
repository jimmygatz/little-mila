# little-mila

Little Mila in Progress — a daily pregnancy companion site.

A single-file website (`index.html`, no build step) that computes the
gestational day live and shows: a day counter and progress orb, week-by-week
baby development, a true-to-scale size ruler, an animated heartbeat, a
hormone chart with a daily readout, milestones, a countdown calendar, and a
chat that answers questions about the baby.

## Deployment

Hosted on Vercel, connected to this repository — every push to `main`
deploys automatically. PWA icons and `manifest.json` support
Add-to-Home-Screen on mobile.

The chat requires an Anthropic API key, pasted once in the app (💬 → paste →
Save); it is stored only in the browser's local storage on the device.
