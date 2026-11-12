# Hello World Site

A single web page that shows the words "Hello World" in large gradient letters on a dark purple background. It is a minimal starter site and a small example of modern CSS.

## What it does

- Displays a centered "Hello World" heading with a purple, blue and green gradient.
- Fades the heading in when the page loads.
- Scales the text to fit any screen size.

## Tech stack

- HTML5
- CSS3 (gradients, `clamp()`, keyframe animation, `background-clip: text`)
- No JavaScript, no dependencies, no build step

## Try it

The whole site is the static file `index.html`.

Open it directly in a browser:

```bash
open index.html        # macOS
xdg-open index.html    # Linux
```

Or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Hosting a live demo

There is nothing to build. Upload `index.html` (or the repository root) to any static host, such as GitHub Pages, Netlify or Vercel. No secrets or environment variables are needed.

## Status

Working. It is a finished, tiny demo.

## Credits

Written by Max Awad. No third-party code is used.
