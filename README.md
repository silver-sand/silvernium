# Silvernium iOS 26 ClearLiquid (Vencord)

Theme structure currently in this repo:

- `MidnightNebula.theme.css` is the entry file.
- It imports hosted files via raw GitHub URLs:
You now have the exact structure you asked for:

- `MidnightNebula.theme.css` imports
  - `main.css`
  - `vencord.css`

## Notes

- `main.css` is the editable ClearVision-style base with deep-blue liquid background tokens.
- `vencord.css` is the editable Vencord layer.
- `MidnightNebula.theme.css` contains the Liquid Glass overlay and Silvernium branding/readability fixes.
- If the theme looks like default Discord, make sure the raw GitHub URLs are serving the latest `main.css` and `vencord.css` from your `silvernium.github.io` repo.
- `main.css` is your local editable ClearVision-style base.
- `vencord.css` is your local editable Vencord layer.
- `MidnightNebula.theme.css` adds iOS 26 liquid-glass overlays and Silvernium branding fixes.
# Silvernium ClearLiquid (Vencord)

Now structured exactly as requested:
- `MidnightNebula.theme.css` (theme entry with imports)
- `main.css` (your editable local ClearVision-style main base)
- `vencord.css` (your editable local Vencord-specific styles)

## Why this setup

You can edit `main.css` and `vencord.css` directly without relying on ClearVision upstream files, while still keeping the import-style architecture you wanted.

## Install

1. Keep all 3 files together (`MidnightNebula.theme.css`, `main.css`, `vencord.css`).
2. Import `MidnightNebula.theme.css` in Vencord themes.
# Silvernium iOS 26 Liquid Glass (Vencord)

Now tuned to be much closer to **ClearVision-style transparency/translucency**, while staying fully local and modular.

## Structure

- `MidnightNebula.theme.css` → main modular entrypoint
- `css/00-settings.css` → ClearVision-like tokens and theme shading variables
- `css/10-layout.css` → transparent/translucent app/layout surfaces
- `css/20-interactions.css` → channel/button behavior + Vencord UI styling
- `css/30-branding.css` → Silvernium branding/nameplate overrides
- `css/40-accessibility.css` → reduced-motion accessibility
- `Silvernium.bundle.css` → merged single-file fallback

## Usage

1. Try `MidnightNebula.theme.css` first.
2. If local imports fail, use `Silvernium.bundle.css`.
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
# ClearVision iOS 26 Liquid Glass (Vencord)

This theme now uses **ClearVision v7** as the base and layers an iOS 26-style Liquid Glass treatment on top.

## What changed

- Uses ClearVision imports (`main.css`, `betterdiscord.css`, `vencord.css`).
- Deep-blue dark backdrop and stronger translucent glass materials.
- Refractive sheen animation on key containers.
- Floating bottom composer treatment (Discord analog to floating tab bar feel).
- Rounded pill controls and liquid popout/modal cards.

## Install

1. Save `MidnightNebula.theme.css`.
2. Open Discord with Vencord.
3. Go to **Settings → Vencord → Themes**.
4. Import/add the file and enable it.

## Customize

Edit `:root` variables:
- `--main-color`, `--hover-color` for primary accents.
- `--background-image` and `--background-filter` for overall atmosphere.
- `--lios-glass-*` for glass/refraction strength.

## Notes

- This depends on ClearVision-hosted imports being reachable.
- Includes `prefers-reduced-motion` and `prefers-reduced-transparency` fallbacks.
# LiquidOS 26 (Vencord Theme)

A custom Discord theme for **Vencord** inspired by an iOS-style **liquid glass** UI:
- frosted translucent panels,
- soft luminous gradients,
- rounded floating surfaces,
- bright cyan/lavender accents.

## Install

1. Save `MidnightNebula.theme.css` on your computer.
2. Open Discord with Vencord.
3. Go to **Settings → Vencord → Themes**.
4. Import/add the CSS file.
5. Enable the theme.

## Personalize the look

Edit variables in `:root` near the top of the CSS file:

- `--lios-accent`, `--lios-accent-2` → accent gradients for pills/buttons.
- `--lios-glass`, `--lios-glass-strong` → glass transparency level.
- `--lios-radius-*` → corner roundness.
- `--lios-bg-*` → base dark gradient backdrop.

## Compatibility notes

Discord internal class names can change after updates. If part of the UI loses styling, update the related selector blocks in the theme file.
