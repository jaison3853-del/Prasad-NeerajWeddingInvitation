# Prasad & Neeraja — Wedding Invitation

A responsive wedding invitation with a scroll-controlled film, the original opening cover, ceremony and reception details, a countdown, and a church location link.

The film moves forwards and backwards with native scrolling. The timeline supports keyboard input; reduced-motion preferences start with animation disabled. The film is muted.

## Run locally

```sh
python3 -m http.server 8000
```

Open the local server in a browser. There are no build steps or package dependencies.

## Deploy on Vercel

Import this GitHub repository into Vercel and set the project name to `prasad-neeraja-wedding` if available. Use the **Other** framework preset, leave the build command empty, and use `.` as the output directory. The included `vercel.json` supplies these settings.

Vercel assigns the project's available `vercel.app` address after deployment. A separate custom domain requires a domain you own and its DNS configuration.

## Files

- `index.html`: invitation, embedded fonts, loader, styles, and scroll interaction
- `assets/wedding-scroll.mp4`: supplied video optimized for seeking
- `assets/wedding-poster.jpg`: poster and loading fallback

Keep `index.html` and `assets/` together when deploying.
