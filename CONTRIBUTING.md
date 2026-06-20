# Contributing

Thanks for taking an interest in Planetary Researcher.

This is a small browser game built with plain HTML, CSS, and JavaScript. Please keep changes focused and easy to test.

## Local Testing

1. Open `index.html` in a browser.
2. Test a short exploration session.
3. Run a syntax check if Node is available:

```bash
node --check js/*.js
```

## Style Notes

- Keep the interface compact and field-computer-like.
- Prefer scientific mystery over direct tutorial language.
- Avoid adding dependencies unless they clearly simplify the project.
- Keep saves backward-compatible when changing state shape.

## Useful QA Seed

```text
anomaly-qa-06-10
```

Land on `TrES 6361e` and test anomaly discovery at `(-7, 12)`, `(-2, 12)`, or `(8, -3)`.
