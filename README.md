
*A glorified plastic toy… powered by actual physics.*

---

No batteries.  
No frameworks.  
No "enterprise solution."

Just HTML5 Canvas, raw JavaScript, and water that behaves like water.

---

## What This Is

Hydro-Jet 3000 is a browser-based version of that nostalgic handheld water ring toy you probably annoyed your parents with.

Except this one:

- **Has real buoyancy.**
- **Has actual drag.**
- **Has collision resolution that doesn't cheat.**
- **And runs at 60 FPS without importing half of npm.**

It's one file.  
Open it. It works. Done.

---

## How You Play

Your job is simple: **Get all 7 rings onto the poles.**

How? By abusing water pressure like a tiny hydraulic engineer.

### Controls

- **A or ←** → Left jet
- **D or →** → Right jet
- Or just press the buttons on screen like a civilized human.

**Hold to build pressure.**  
**Tap for precision.**  
**Spam and you'll regret it.**

---

## What Makes It Actually Interesting

This isn't "move ring up when button pressed."

There's a real physics loop under the hood:

- Gravity pulls everything down.
- Buoyancy pushes things up.
- Water drag slows motion.
- Jets build power over time.
- Rings collide with each other.
- Rings only land on poles if they approach from above.
- They slide and stack naturally.

**No teleporting.**  
**No fake snapping.**  
**If it lands, it earned it.**

---

## Tech Stack (aka "just code")

- HTML5 Canvas
- Vanilla JavaScript (ES6)
- requestAnimationFrame
- Web Audio API (optional sound)

That's it.

If your browser was built after dinosaurs, it'll run.

---

## Physics Philosophy

Everything is based on simple Newtonian motion:

```
velocity += gravity
velocity *= damping
position += velocity
```

Then we layer:

- Water current fields
- Turbulence
- Convection
- Ring-to-ring impulse resolution
- Constraint correction for pole stacking

It's controlled chaos. Like real water. But friendlier.

---

## Performance

- **Smooth at 60 FPS**
- **No external libraries**
- **No build tools**
- **No "install dependencies"**
- **No "please update Node"**

You double-click the file. It runs.  
Revolutionary concept, I know.

---

## Customizing It

Want more chaos?

- Increase buoyancy.
- Increase jet power.
- Reduce drag.

Break it. That's half the fun.

All physics values live in one object. Tweak and reload.

---

## Why This Exists

Because:

- Nostalgia deserves physics.
- Toys shouldn't be fake.
- And sometimes building something unnecessarily accurate is the point.

Also, it's a solid Canvas + physics portfolio piece.

---

## File Structure

```
hydro-jet-3000/
└── index.html   (the whole thing lives here)
```

One file.  
Like it should be.

---

## Author

Built by **Yoganjaneyulu**

*Future over-engineer of simple things.*

---

*Do whatever you want with it.*  
*Just don't remove the physics and call it realistic.*
