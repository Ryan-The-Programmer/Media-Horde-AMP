# Contributing

Keep changes boring and maintainable.

## Ground rules

- Keep `playlist.txt` next to `index.html`
- Keep media paths relative
- Do not re-introduce a giant hardcoded JavaScript library array
- Keep the app static-host friendly
- Prefer small files and focused commits over one giant mystery blob

## Suggested workflow

1. Make changes in a feature branch
2. Test with both:
   - a local `file://` open using manual playlist loading
   - a tiny HTTP server or GitHub Pages
3. Rebuild `playlist.txt` if the sample library changed
4. Update the README if behavior changed

## Code style

- Vanilla HTML/CSS/JS only
- Keep modules separate
- Avoid adding framework baggage unless there is a truly good reason, which there usually is not
