# ThreadSwitcherMockup

A lightweight UX mockup for a “Quick Open” thread switcher (Command Palette style). It simulates
keyboard navigation across threads and a realistic conversation view.

> Submitted to issue [#6500](https://github.com/openai/codex/issues/6500)

## Live Demo

- GitHub Pages: https://lpcode808.github.io/ThreadSwitcherMockup/

## Features

- Command palette quick open (`⌘ O` / `Ctrl O`)
- Search across thread titles and message bodies (title matches ranked higher)
- Highlighted search results + message snippet previews
- Keyboard navigation for results and thread list
- Realistic sample conversation transcripts

## Shortcuts

- `⌘ O` / `Ctrl O` — Open quick switcher
- `↑` / `↓` — Navigate results
- `⌘ J` / `⌘ K` — Navigate results (palette open)
- `Enter` — Open selected thread
- `Esc` — Close palette
- `⌘ J` / `⌘ K` — Switch threads (palette closed)

## Local Run

Open `index.html` directly in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
