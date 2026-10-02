# Oldagram — Instagram Feed Clone

A front-end recreation of the Instagram feed UI, dynamically rendered from a data array rather than hardcoded HTML — built to practice turning structured data into a real, scrollable social feed.

## Features

- Scrollable post feed with profile avatar, name, and location per post
- Like, comment, and DM icon row per post
- Like count formatted with locale-aware number formatting (e.g. `1,234` likes)
- Fully data-driven — posts are rendered from a JavaScript array of post objects, not written individually in HTML

## Tech Stack

`HTML` · `CSS` · `JavaScript` · `Vite`

## Key Concepts Demonstrated

- Rendering a dynamic UI from an **array of objects**, not static markup
- Template literals for building repeated, structured HTML blocks
- Looping and string concatenation to construct a full feed from data
- Clean separation of data (post content) from presentation (markup/CSS)
- Working with image assets and structured project layout

## Run Locally

```bash
git clone https://github.com/Abdullah326dev/oldagram-Insta-clone-.git
cd oldagram-Insta-clone-
npm install
npm run dev
```

## Potential Next Steps
- Make the like button interactive (increment/toggle like count on click)
- Add a "post a comment" input
- Pull post data from a real backend (e.g. Firebase) instead of a static array
