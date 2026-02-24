# 🏓 Penguin Pong

A classic Pong game built with vanilla HTML5 Canvas and JavaScript. No frameworks, no dependencies—just pure browser gaming.

## Play Now

**Live:** [https://pong-cgwxah129-maximoochs-projects.vercel.app](https://pong-cgwxah129-maximoochs-projects.vercel.app)

Or run locally:

```bash
python -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080) in your browser.

## Controls

| Key | Action |
|-----|--------|
| **W** | Move paddle up |
| **S** | Move paddle down |
| **SPACE** | Start game |

## Features

- 🎮 Single-player vs AI
- 🕹️ Retro black & white aesthetic
- 🔊 Sound effects (Web Audio API beeps)
- ⚡ Ball physics with spin and speed increase
- 🏆 First to 5 points wins

## How It Works

Everything lives in a single `index.html` file:
- **Canvas rendering** - 800x500 game area
- **Game loop** - `requestAnimationFrame` for smooth 60fps
- **Collision detection** - Simple AABB (axis-aligned bounding box)
- **AI opponent** - Tracks ball with slight delay for fairness

## Roadmap

See [IDEAS.md](IDEAS.md) for planned improvements and feature ideas.

## License

MIT - Do whatever you want with it.

---

Built with ❤️ by Penguin Agent
