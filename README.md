# 🎡 Streamer Spin The Wheel

A fast, lightweight, zero-dependency giveaway wheel designed specifically for streamers. Built entirely with **HTML5, CSS3, and JavaScript**.

---

## ✨ Features

1. **Cyber Obsidian & Holographic Nebula Theme:**
   - Deep obsidian space aesthetic with smooth iridescent ambient glows and grid overlay.
   - Refined typography using **Plus Jakarta Sans** and **Chakra Petch**.
   - Cohesive glassmorphism cards and harmonized button geometry.

2. **Native Twitch IRC Chat WebSocket:**
   - No login, client secret, or OAuth token required.
   - Connects directly to any public Twitch channel chat via anonymous WebSocket IRC.
   - Robust IRC tag parser (`display-name`, `badges`, etc.) extracts viewer names seamlessly.

3. **Customizable Join Command:**
   - Supports any command you choose (default: `!join`).
   - Case-insensitive (matches `!join`, `!JOIN`, `!Join`).
   - Automatically prevents duplicate entries.

4. **Live Chat Activity Feed:**
   - Real-time chat activity monitor in the sidebar so you can see incoming messages immediately.
   - Instant badges: `[Added to Wheel]`, `[Already Joined]`, `[Entries Paused]`.

5. **One-Click Pause / Resume:**
   - Toggle button: **"Entries Open 🟢"** / **"Entries Paused 🔴"**.
   - Stop viewers from entering at any moment during explanations or spins.

6. **Realistic Wheel Physics & Sound FX:**
   - HTML5 Canvas with High-DPI / Retina display support.
   - Mechanical tick sound as pegs hit the top pointer.
   - Victory fanfare and confetti explosion upon selecting a winner (via Web Audio API, works 100% offline).

7. **Harmonious Winner Modal & Post-Win Actions:**
   - Glowing halo backdrop and luminous winner card.
   - **🗑️ Remove from Wheel:** Clean crimson glass button with glowing border.
   - **🔄 Keep & Spin Again:** Luminous electric cyan-to-purple gradient button.
   - **Keep participant & close:** Subtle ghost link dismiss button.

8. **OBS Studio Overlay Mode:**
   - Press **`O`** or click the OBS icon to hide controls and isolate the transparent wheel for clean broadcasting.

9. **Developer Footer:**
   - Links directly to [alaqra.dev](https://alaqra.dev).

---

## 🚀 How to Run

1. Simply double-click [`index.html`](file:///d:/Projects/SpinTheWheel/index.html) to open it in Chrome, Edge, or Firefox.
2. Enter your **Twitch Channel Name** and click **Connect**.
3. Set your **Join Command** (e.g. `!join`).
4. Ask your viewers to type the command in chat — they will instantly appear on the wheel and in the Live Chat Activity feed!
5. Click **SPIN THE WHEEL** (or press the **Spacebar**).

---

## ⌨️ Keyboard Shortcuts

- **Spacebar:** Spin the wheel immediately.
- **Key `O`:** Toggle clean OBS mode on/off.
- **Enter:** Submit channel connection or manual name addition.
