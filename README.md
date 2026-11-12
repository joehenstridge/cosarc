# CoSARC Website — static site export

This is the CoSARC website redesign as plain HTML/CSS, ready to host on
GitHub Pages (or any static host).

## Files

- `index.html` — Home
- `join-us.html` — Join Us
- `training.html` — Training (Track & Field + Distance & XC)
- `events.html` — Events (Salisbury 10 Mile, Stonehenge Stomp, leagues)
- `news.html` — Club News
- `about.html` — About (About Us, Governance, Safeguarding, Contact, Emergency Contacts)
- `styles.css` — shared stylesheet
- `cosarc-logo.png` — the club badge, used as the header logo and favicon

## Publishing to GitHub Pages

1. Create a new GitHub repository (or use an existing one).
2. Add these files to the repository root (or to a `/docs` folder — just
   match whatever you tell GitHub Pages to serve).
3. In the repo's **Settings → Pages**, set the source to the branch/folder
   you used, then save.
4. GitHub will give you a URL like `https://<username>.github.io/<repo>/`
   within a minute or two.

If you want a custom domain (e.g. `www.salisbury-arc.org`), add a `CNAME`
file containing just that domain, and point your DNS at GitHub Pages per
GitHub's instructions.

## Still placeholders — needs your input before this goes live

A few links intentionally still point to `#` because the real target
doesn't exist yet. Search for `href="#"` to find them all, or see the list
below:

- **Join Us** — "Download the Welcome Pack" and "Download Membership &
  Fees" (no PDF files were provided)
- **About → Governance** — "Club governance documents" link, and the
  governance section's body text (marked with `[...]`)
- **About → Safeguarding** — "Child Policy" and "Adult Policy" links
- **About → Emergency Contacts** — the whole section is a placeholder
  (marked with `[...]`) — the original site's Emergency Contacts page
  didn't load when this was built, so its real content never made it in
- **Events** — "Southern Athletics League", "Wessex Young Athletes
  League" and "County championships & fixtures" (couldn't confirm real
  URLs); the other five league links do point to their real pages
- **News** — "Read more" on both articles (no full article content was
  available)
- Photography — every `[ photo ]` / `[ club photography ]` box is a
  placeholder for a real image

Everything else — the main navigation, the Training page's jump links,
footer links, and every `@salisbury-arc.org` email address — is wired up
to a real destination.

## Design notes

- Colour palette is based on the real CoSARC brand blue, sampled from the
  live salisbury-arc.org site and its logo.
- The layout was originally drawn at a fixed desktop width; this export
  adds a light responsive pass (`styles.css`, bottom section) so it
  doesn't break on a phone, but it hasn't been exhaustively tested across
  devices — check it on a few screen sizes before pointing a real domain
  at it.
