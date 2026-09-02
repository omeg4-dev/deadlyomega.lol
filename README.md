<div align="center">

# 🌐 deadlyomega.lol

**My corner of the internet.**

A cyberpunk landing page with a door you have to open first.

🔗 **[deadlyomega.lol](https://deadlyomega.lol)**

</div>

---

### ✨ What it does

🚪 **An enter screen.** Nothing plays until you press the button — which is also what lets the
music start, since browsers won't autoplay audio without a gesture.

⌨️ **Typed and scrambled text.** The name types itself in; the subtitle scrambles through
random characters before settling.

✨ **Particles, aurora, scanlines.** Three drifting aurora blobs, a `tsparticles` field, and a
scanline overlay over the whole thing.

🎞️ **A video background**, muted and looping behind everything.

🪞 **Tilt with glare.** The card leans toward your cursor — `vanilla-tilt` at 3° with a glare
layer.

### 🧰 Built with

| | |
|---|---|
| [tsparticles](https://particles.js.org/) | the particle field |
| [typed.js](https://mattboldt.com/demos/typed-js/) | the typing effect |
| [vanilla-tilt](https://micku7zu.github.io/vanilla-tilt.js/) | the lean and the glare |
| Orbitron | the typeface |

No framework, no build step — three files and a GitHub Pages workflow.

### 🛠️ Local

```sh
python -m http.server 8000    # then open localhost:8000
```

Deploys itself from `main` via `.github/workflows/static.yml`.

---

<div align="center"><sub>Earlier versions live in <code>old/</code></sub></div>
