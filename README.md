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
