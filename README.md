# Bubbles — Progress Tracker

Single-file HTML view of where the Bubbles project stands against its vision document. Each section mirrors a layer of that vision; percentages measure architectural alignment + readiness, not feature-completeness against an end-state.

The principal's external progress view — separate from Bubbles' internal vision tracker, which is a kernel-side sub-program with its own state.

## Live

Hosted via GitHub Pages — `index.html` redirects to `tracker.html`.

## Local view

Open `tracker.html` directly in any browser — no server needed. All data lives in the `DATA` block inside `tracker.html`; edit it to refresh the view.

## Updating

```
git add tracker.html
git commit -m "tracker: <what changed>"
git push
```

GitHub Pages re-deploys on every push.
