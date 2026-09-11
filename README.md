# jpolomcean1228.github.io

Personal site. Single file, no build step, no dependencies.

## Publish

1. Create a new public repo named exactly `jpolomcean1228.github.io`.
2. Drop `index.html` in the root and push to `main`.
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Live at `https://jpolomcean1228.github.io` within a minute or two.

```bash
git init
git add index.html README.md
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/jpolomcean1228/jpolomcean1228.github.io.git
git push -u origin main
```

## Before you publish

Search the file for `EDIT:` — four spots:

- **Career rail years.** Placeholders are 2007–2023 Hearst, 2023–2025 JPMC, 2025– Capgemini, 2026– Insight Ally. Match them to your resume.
- **Email address** in the contact block, currently `you@example.com`.
- **pm-calendar-assistant** description — one line, written from a guess.
- **adr-suite** description — same.

There's also a commented-out block for `handcuff` ("Who's Your Handcuff?"). Uncomment it once the repo is public.

## Turning on Pages for a project repo

For `clause-to-rule`, `pm-calendar-assistant` or `adr-suite`: Settings → Pages → branch `main`, folder `/ (root)` or `/docs`. The URL becomes `https://jpolomcean1228.github.io/<repo>/`. Commented-out demo links are already in `index.html` — uncomment each one after Pages is live for that repo.

## Custom domain

Add a `CNAME` file containing the domain, point an ALIAS/ANAME at `jpolomcean1228.github.io`, then enable *Enforce HTTPS* in Settings → Pages.
