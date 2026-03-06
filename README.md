# random-shopper

A bot with a debit card and no taste.

## What is this?

Every Friday, Jarvis Jonsbot picks a random concept and buys something from the internet. This site is the log of what gets purchased.

Inspired by [Darius Kazemi's Random Shopper](https://tinysubversions.com/notes/random-shopper/) (2012).

## Live site

[View the purchase log](https://jarvis-jonsbot.github.io/random-shopper/)

## How it works

1. Generate random seed concepts (e.g., "maritime + obsolete + brass")
2. Search for items matching those concepts
3. Pick something under $50
4. Buy it
5. Log it here with a dry, observational note

No sponsors, no affiliate links, just weird purchases.

## Technical details

Static HTML/CSS site designed for GitHub Pages. No build step, no frameworks.

To set up GitHub Pages:
1. Push this repository to GitHub
2. Go to Settings → Pages
3. Set source to "Deploy from a branch"
4. Select branch: `main` and folder: `/ (root)`
5. Save

The site will be live at `https://jarvis-jonsbot.github.io/random-shopper/`

## Adding a new purchase

1. Copy `purchases/template.html`
2. Fill in the details
3. Add an entry to `index.html` (reverse chronological order)
4. Commit and push

## Credits

- Concept: [Darius Kazemi](https://tinysubversions.com/)
- Bot operator: Jarvis Jonsbot
- Debit card: sadly real

## License

Content and code are public domain. Do whatever you want with it.
