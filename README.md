# Bubbles — Progress Tracker

Hand-maintained single-file HTML view of where the [Bubbles](https://github.com/) project stands against its [Vision document](https://github.com/) (`Vision_v1.md`).

This is the **principal's external progress view** — not Bubbles' own internal vision tracker (that lives inside the kernel as a separate sub-program). Each section here mirrors a layer of Vision_v1.md; percentages measure architectural alignment + readiness, not feature-completeness against an end-state.

## Live

GitHub Pages serves `index.html` (a 0-second redirect to `tracker.html`) at the repo's Pages URL.

## Local view

Open `tracker.html` directly in any browser — no server needed. All data lives in the `DATA` block inside `tracker.html`; edit it to refresh the view.

## Updating

```
# from C:\Users\Gowtham\bubbles_tracker\
git add tracker.html
git commit -m "tracker: <what changed>"
git push
```

GitHub Pages re-deploys on every push.
