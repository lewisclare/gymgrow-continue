# GymGrow Continue

Winback pages for clients who give churn notice. Static HTML, deployed by Vercel (project `gymgrow-continue`).

- `index.html`: the generic page, at gymgrow-continue.vercel.app/
- `<client>/index.html`: one folder per client, at gymgrow-continue.vercel.app/<client>/
- Shared images sit in the root; client pages reference them as `../logo-white.png`.

## Adding a client page

1. Copy an existing client folder and rename it (lowercase, e.g. `mova`).
2. Fill it from that client's cancellation analysis: their results first, then their reason for leaving answered, then the options (stay and change what's not working, Pro, Software).
3. Never show the price of the client's current plan.
4. Open a pull request. Merging it puts the page live. Nothing is sent to the client until it has been reviewed.
