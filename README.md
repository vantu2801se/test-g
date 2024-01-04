![](slasher.jpg)

# slasher-prototype
Game prototype. 2.5D perspective view. Levels loader, the hero controller, monsters and basic AI logic.
Gamepad and keyboard binding supported.
LUA. Defold engine.

## HTML5 demo
Try here: [demo](https://dragosha.github.io/slasher-prototype/)

## Code
**Used dependencies:**
* Defold-input (by britzl)
* Rendercam (by rgrams)
* ludobits (by britzl)

## Level design
![](docs/level.jpg)
tip: use ```Ctrl(cmd)+LeftMouse``` to rotate camera in the editor.

Notice: Y-coordinate of gameobject used as pivot for auto-correction Z-coordinate for perspective view of scene. See: scene.script > load_complete function.

![](docs/pivot.png)

**Composite object:**

![](docs/composite.png)
- contains 2 sprite component, one for a front plane, second for a top plane with rotating around X-axe


