# Zenitsu Katana — Special Attack

## Input
Use a dedicated in-game special-attack button. The ability should only activate while the Zenitsu katana is equipped.

## Visual sequence
1. Brief yellow-white flash around the player.
2. A short, fast forward dash in the facing direction.
3. A jagged yellow lightning trail follows the dash.
4. A brighter final flash marks the end of the move.
5. Return control to normal movement.

## Gameplay boundaries
- This is a stylized fantasy effect inside Stardew Valley.
- No gore or realistic weapon technique.
- Keep the effect short and readable; avoid covering the whole screen.
- Add a cooldown so the special cannot be triggered continuously.

## Implementation note
The current repository is a Content Patcher content-pack skeleton. A dedicated SMAPI code project is needed for a custom button, dash timing, cooldown, and drawn lightning effect. Android touch-button support must be verified in the target SMAPI Android runtime before claiming the button is functional.
