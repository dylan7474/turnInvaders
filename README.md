# Turn Invaders

Turn Invaders is a lightweight, browser-based tactical space skirmish game built in a single `index.html` file. You command a three-ship squad, roll action points each turn, and use movement, rotation, weapons, shields, and repairs to survive enemy waves sector by sector.

## Run locally

No build step is required.

1. Clone the repository.
2. Start a static server from the project root:
   ```bash
   python3 -m http.server 8000
   ```
3. Open `http://localhost:8000` in your browser.
4. Click **INITIALIZE SYSTEMS** to enable audio and begin.

> You can also open `index.html` directly, but running a local server is the most reliable setup.

## Basic controls

### Keyboard
- `W`: Move forward
- `S`: Move backward
- `A`: Rotate left
- `D`: Rotate right
- `F`: Fire phaser
- `Q`: Toggle shield
- `Space`: End player turn
- `E`: End player turn (alternate key)

### Mouse / UI
- Click ship tabs (`ALPHA`, `BRAVO`, `CHARLIE`) to switch active ship.
- Click action buttons to execute abilities, including **FIELD REPAIR**.

## HUD and craft identification

- Your squad ships are shown as **ALPHA**, **BRAVO**, and **CHARLIE** in the ship tabs, while each craft itself carries the compact callsign marker: **A**, **B**, and **C**.
- The active ship panel now shows a **HULL** readout. **HULL** means the craft's core frame integrity (whether the ship is still operational).
- Shield bars (`SHIELD`) are separate from HULL and represent temporary protection that can be toggled and repaired.

## Short roadmap

- Add win/lose screens and sector progression summary.
- Improve enemy AI behavior and movement variety.
- Split game logic into modular JavaScript files for easier maintenance.
- Add optional difficulty presets and score tracking.
