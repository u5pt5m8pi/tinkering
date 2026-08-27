# A11y notes from tinkering

- Use `aria-labelledby` instead of `aria-label` when a visible label exists.
- `aria-current="page"` for current nav item.
- For disclosure buttons, toggle `aria-expanded` and keep `aria-controls` pointing at the panel.
- Don't use `role="alert"` on page load; prefer live regions with `aria-live="polite"` unless it's a real, time-sensitive error.
- `:focus-visible` is for keyboard focus, not mouse clicks.
- Test one page with a screen reader before reaching for a widget library.
