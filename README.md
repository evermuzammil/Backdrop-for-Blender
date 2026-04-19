# Backdrop — One Click Cyclorama for Blender

**Backdrop** is a Blender add-on that creates a studio-style cyclorama (infinite background wall) in a single click. Select your object, hit **Create Backdrop**, and a perfectly positioned, smoothly curved backdrop is generated right under it — ready to render.

Available on the [Blender Extensions Platform](https://extensions.blender.org/approval-queue/backdrop/).

---

## Features

- **One-click creation** — generates a full cyclorama instantly
- **Auto-snaps to your object** — detects the bottom of your selected mesh and places the floor exactly underneath it
- **Smooth curved transition** — floor-to-wall curve is handled automatically with a bevel modifier
- **Modular walls** — optionally add left wall, right wall, and top wall
- **Floor only mode** — just a flat floor if that's all you need
- **Shadow Catcher support** — toggle directly from the panel for compositing workflows
- **Custom color** — set the backdrop color with a full color picker before creating
- **Non-destructive parameters** — adjust width, depth, height and curve size after creation from Blender's operator panel, position stays locked

---

## Installation

### Option 1 — Blender Extensions Platform *(recommended)*
1. In Blender, go to `Edit > Preferences > Get Extensions`
2. Search for **Backdrop**
3. Click **Install** — done!

### Option 2 — Install from Disk
1. Download the latest `.zip` from the [Releases](../../releases) page
2. In Blender, go to `Edit > Preferences > Get Extensions`
3. Click the dropdown arrow (top right) → `Install from Disk`
4. Select the downloaded `.zip`
5. The addon will appear in the **N-panel** under the `Backdrop` tab

**Requires Blender 5.1 or newer.**

---

## Usage

1. *(Optional)* Select a mesh object — the backdrop will snap its floor to the base of the object
2. Open the **N-panel** (`N` key in viewport) → go to the `Backdrop` tab
3. Pick a color if needed
4. Click **Create Backdrop**
5. Adjust **Width**, **Depth**, **Height**, **Curve Size** and wall toggles from the operator panel in the bottom-left corner

---

## Parameters

| Parameter | Description |
|---|---|
| Width | Total width of the backdrop |
| Depth | Total depth of the backdrop |
| Height | Height of the back wall |
| Curve Size | Size of the smooth floor-to-wall transition |
| Left Wall | Adds a left side wall |
| Right Wall | Adds a right side wall |
| Top Wall | Adds a ceiling connecting to the back wall |
| Floor Only | Creates just the floor plane with no walls |
| Shadow Catcher | Marks the backdrop as a shadow catcher for compositing |

---

## License

GNU General Public License v3.0 or later — see [LICENSE](LICENSE) for details.
