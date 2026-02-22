# Silvernium iOS 26 Liquid Glass (Vencord)

Theme is now organized into **modular local CSS files** plus a fallback bundled file.

## File structure

- `MidnightNebula.theme.css` → main entrypoint that imports everything.
- `css/00-settings.css` → tokens and variables.
- `css/10-layout.css` → backgrounds, panels, composer sizing.
- `css/20-interactions.css` → hover, flicker fix, squishy buttons.
- `css/30-branding.css` → wordmark/nameplate overrides.
- `css/40-accessibility.css` → reduced motion handling.
- `Silvernium.bundle.css` → fully merged fallback (single file).

## Recommended usage

1. Try `MidnightNebula.theme.css` first (modular).
2. If your client fails local `@import`, switch to `Silvernium.bundle.css`.

## Current behavior

- Silvernium nameplate replacement.
- Squishy button press/fade interaction.
- No periodic faint moving background.
- Smaller typing/composer box.
- Hover flicker fix retained.
