# Twitter-Clone

A small Scrimba learning project that recreates the core interactions of a microblog feed using vanilla JavaScript, Vite, static data, and browser-side state.

## Why I Built This

I built this as part of my Scrimba full-stack/frontend learning path to practice DOM rendering, event delegation, state updates, conditional UI classes, and simple component-like HTML generation without a frontend framework.

## Features

- Renders a static tweet feed from `data.js`.
- Like and unlike tweets with live count updates.
- Retweet and un-retweet tweets with live count updates.
- Toggle reply threads open and closed.
- Compose a new tweet and insert it at the top of the feed.
- Generates IDs for new tweets using `uuid` from JSPM.
- Uses Font Awesome icons and a small custom CSS layout.

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript ES modules
- Vite
- Font Awesome CDN
- Google Fonts
- JSPM `uuid` import

## My Role / Contribution

Built as a Scrimba learning project. The implementation focuses on frontend fundamentals rather than production architecture.

## Project Structure

```text
Twitter-Clone/
|-- README.md
|-- package.json
|-- vite.config.js
|-- index.html
|-- index.css
|-- index.js
|-- data.js
`-- images/
```

## Getting Started

### Prerequisites

- Node.js 18+

### Installation

```bash
git clone https://github.com/Ph0enix19/Twitter-Clone.git
cd Twitter-Clone
npm install
```

### Environment Variables

No environment variables are required.

### Run Locally

```bash
npm run dev
```

Open the local Vite URL in your browser.

## Screenshots / Demo

- [TODO: add screenshot of the Twimba feed]
- [TODO: add short GIF showing like, retweet, replies, and new tweet creation]
- [TODO: add screenshot/live demo]

## Current Status

Learning project. It demonstrates frontend interaction basics, but it does not include authentication, a backend, persistent storage, responsive redesign, accessibility review, or tests.

## Future Improvements

- Replace the remote JSPM import with a package dependency or a small local ID helper.
- Save tweets to `localStorage`.
- Add delete/edit tweet interactions.
- Improve responsive layout beyond the current narrow feed.
- Add basic accessibility labels for icon buttons.
- Add screenshots and a live deployment link.

## What I Learned

- How to render UI from an array of objects.
- How to use event delegation through `data-*` attributes.
- How to update state and re-render the DOM after interactions.
- How small projects still benefit from clear README structure and honest scope.
