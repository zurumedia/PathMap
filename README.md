# PathMap

**Find the course that actually fits you.**

PathMap is a guided web app that helps tertiary students in Nigeria figure out what to study. Instead of generic advice or a chatbot guessing on your behalf, it asks a short series of structured questions about what you enjoy, what you're good at, and what you want out of a career — then matches your answers against a set of common courses and suggests the ones that genuinely fit.

## Live Demo

🔗 pathmap.ng (replace with your live GitHub Pages / domain link)

No sign-up. No login. Takes about 6–9 minutes.

## How It Works

PathMap runs entirely in the browser — there's no backend or account system.

1. Five quick-pick questions — subjects you enjoy, what you're naturally good at, the environment you'd want to work in, what you value most in a career, and the kind of work that sounds enjoyable. Each choice is scored against a set of traits (analytical, creative, technical, people-facing, and so on).
2. Five reflection questions — what's actually on your mind, why it matters to you, whether you've talked to anyone already doing it, what success would look like, and one real step you can take this week.
3. Your PathMap — a result screen showing your top matching courses (with a short reason for each), an honest reality check, and one concrete next step. You can save it to your device and come back to it later.

The course-matching logic is rule-based and transparent — not AI-generated — so the same honest answers will always point to the same suggestions.

## Features

- Guided, judgment-free question flow (no rushed decisions, no jargon)
- Course suggestions backed by a visible reason, not a black box
- Personal, on-device library of saved PathMaps (uses localStorage, nothing leaves your browser)
- Light and dark mode, responsive on mobile
- Zero dependencies — a single self-contained HTML file

## Tech Stack

- HTML, CSS, and vanilla JavaScript — no frameworks, no build step
- Google Fonts (Fraunces + Inter) for typography
- Browser localStorage for saving results locally

## Getting Started

Clone the repo and open index.html directly in a browser — that's it.

git clone https://github.com/your-username/pathmap.git
cd pathmap
open index.html

### Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to Settings → Pages.
3. Under Source, select the main branch and / (root) folder.
4. Save — GitHub will publish the site at https://your-username.github.io/pathmap/

## Roadmap

- [ ] Real accounts and persistence across devices
- [ ] Expanded course database
- [ ] Feedback loop from students who've used their suggestions
- [ ] Custom domain (pathmap.ng)

## About

PathMap is built and maintained by Destiny Nicholas / Zuru Media, a creative agency based in Port Harcourt, Nigeria.

## License

© PathMap. All rights reserved, unless you choose to open-source it — add a license file (e.g. MIT) here if you want others to reuse the code.
