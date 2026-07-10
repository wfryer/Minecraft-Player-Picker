# ⛏️ Player Picker

A Minecraft-themed random student selector for classroom mini-games — perfect for picking players, assigning teams, or randomly selecting students to answer questions.

Designed to be incredibly easy to host, this version runs entirely offline as a single HTML file with no dependencies, no server requirements, and no internet required after the initial Google Fonts load.

[View and use this code / spinner on this GitHub webpage](#) *(Note: update with your GitHub Pages link)*

## 🎮 How to Use

1. Open the HTML file in any modern web browser.
2. **Add Players:** In the "PLAYER ROSTER" panel, type or paste the names of the students/players, one per line. The wheel will automatically generate and update as you type.
3. **Select Quantity:** Use the hotbar-style buttons to choose how many players you want to pick at once (1 to 6).
4. **Configure Options:** 
   - Toggle **Remove picked players from the wheel** if you want to avoid picking the same student twice. 
   - Toggle **Sound effects** on or off.
5. Click **SPIN!** (or press the `Space` bar).
6. When the wheel lands, a "PLAYERS SELECTED!" screen appears with Minecraft-style cards, pixel art, and confetti.
7. If you had the remove option toggled, picked players will appear in the "ALREADY PICKED" section. Click an individual name to restore them to the wheel, or click "RESTORE ALL PLAYERS" to start fresh.

## 🎨 Customizing the Look

Near the top of the `<style>` block in the HTML file, you'll find a `:root` section with CSS variables that control the Minecraft-inspired color palette:

    :root {
      --night: #141327;
      --panel: #c6c6c6;
      --grass: #6cbf43;
      --dirt: #8b5a2b;
      --gold: #fcdc5f;
      --diamond: #4aedd9;
      /* ...and many more */
    }

Adjust these hex codes to completely re-theme the page without having to hunt through the rest of the CSS.

## 📚 Classroom Ideas

| Activity | Description |
| :--- | :--- |
| **Mini-Game Selection** | Pick 2-4 students to step up and participate in the next Minecraft build battle or PvP match. |
| **Classroom Jobs** | Spin the wheel to randomly assign daily or weekly classroom responsibilities. |
| **Team Generation** | Pick multiple students at a time to form groups or factions for a larger project. |
| **Random Caller** | Keep students engaged by using the wheel to randomly call on someone to answer a discussion question. |

## 🛠 Technical Notes

* **Single file** — everything is self-contained in one `.html` file (HTML + CSS + Vanilla JS).
* **Auto-Save** — automatically saves your roster and settings to the browser's `localStorage`. If you accidentally close the tab, your list will be waiting for you when you come back!
* **Pixel Art Canvas** — uses HTML5 Canvas to render custom 8x8 pixel art (Creepers, Diamonds, TNT, etc.) directly via code—no external image files required.
* **Fonts** — loads Press Start 2P and VT323 from Google Fonts on first use; falls back gracefully to system monospace fonts if offline.
* **No server needed** — open directly from your file system.
* **Tested in** — Chrome, Firefox, Safari, and Edge.

## 📁 File Structure

* `index.html` (or whatever you named the HTML file) ← the entire app, one file.
* `README.md` ← this file.

## 📄 License & Credits

Feel free to use, modify, and share this freely for educational purposes. A credit link back is appreciated but not required.

Vibe coded by Wes Fryer with Claude for the Minecraft Mini-Game Coding Camp • Press Space to spin. 

Learn more about my (Wes Fryer's) AI vibe coding journey on [ai.wesfryer.com](https://ai.wesfryer.com).
