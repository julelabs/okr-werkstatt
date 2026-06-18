# OKR Werkstatt

Static website for the OKR Werkstatt: OKRKritikBot 3000, learning path, quiz, and toolbox.

## Current Pages

- `index.html` - landing page and bot entry
- `lernpfad.html` - interactive learning path
- `quiz.html` - OKR classification quiz
- `werkzeugkoffer.html` - downloadable tools and materials

## Local Preview

From this folder:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://127.0.0.1:8765/index.html
```

## Notes

- This is currently a static HTML/CSS/JS site.
- `index.html` loads React/Babel from `unpkg.com` for the tweaks panel.
- The surrounding Outcome Office vault folder contains project notes, backlog, references, and deploy exports.
