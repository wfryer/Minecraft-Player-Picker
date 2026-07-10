# ⛏️ Player Picker

A Minecraft-themed random student selector for classroom mini-games — perfect for picking players, assigning teams, or randomly selecting students to answer questions.

Designed to be incredibly easy to host, this version runs entirely offline as a single HTML file with no dependencies, no server requirements, and no internet required after the initial Google Fonts load.

[View and use this code / spinner on this GitHub webpage](#) *(Note: update with your GitHub Pages link)*

## 🎮 How to Use

1. Open the HTML file in any modern web browser.
2. **Add Players:** In the "PLAYER ROSTER" panel, type or paste the names of the students/players, one per line. The wheel will automatically generate and update as you type.
3. **Select Quantity:** Use the hotbar-style buttons to choose how many players you want to pick at once (1 to 6).
4. **Configure Options:** - Toggle **Remove picked players from the wheel** if you want to avoid picking the same student twice. 
   - Toggle **Sound effects** on or off.
5. Click **SPIN!** (or press the `Space` bar).
6. When the wheel lands, a "PLAYERS SELECTED!" screen appears with Minecraft-style cards, pixel art, and confetti.
7. If you had the remove option toggled, picked players will appear in the "ALREADY PICKED" section. Click an individual name to restore them to the wheel, or click "RESTORE ALL PLAYERS" to start fresh.

## 🎨 Customizing the Look

Near the top of the `<style>` block in the HTML file, you'll find a `:root` section with CSS variables that control the Minecraft-inspired color palette:

```css
  :root {
    --night: #141327;
    --panel: #c6c6c6;
    --grass: #6cbf43;
    --dirt: #8b5a2b;
    --gold: #fcdc5f;
    --diamond: #4aedd9;
    /* ...and many more */
  }