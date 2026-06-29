# Tortuga 🐢

**A field guide to the animal kingdom.**

Tortuga shares the wild, weird, true facts about animals — from sea turtles older than the dinosaurs to mantis shrimp that punch like bullets. Built for curious people who want the fun, jaw-dropping stuff, bite-sized.

## About

A single-page interactive field guide featuring 40 animals, each with a set of strange-but-true facts, plus an "About Us" note and a "Save the Planet" section. Animals are listed alphabetically in the sidebar.

## Tech

A self-contained static site — one `index.html` file with all HTML, CSS, and JavaScript inline. No build step required. All animal content lives in a single `ANIMALS` array in the inline `<script>`, and the sidebar and sections are generated from it.

## Local preview

Open `index.html` in any web browser, or serve the folder:

```bash
python3 -m http.server
```

## Deploy

Hosted on Vercel as a static site. Any push to `main` redeploys automatically once the repo is connected to Vercel.
