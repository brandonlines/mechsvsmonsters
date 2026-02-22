# Mechs vs Monsters

Single-file browser survival shooter built with HTML5 Canvas.

## Play Locally

1. Open `index.html` directly in your browser, or
2. Run a local static server for best compatibility:

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

## Controls

- `W A S D` or arrow keys: Move
- Mouse: Aim
- Left click: Fire cannon
- `Space`: Nova Bomb (when charged)
- `Shift`: Sprint (unlocks at wave 2)
- `J`: Flight for 5s (unlocks at wave 3)
- `K`: Nuclear strike charges (unlocks at wave 4)

## Gameplay

- Survive waves of monsters.
- Earn score and kills by defeating enemies.
- Unlock mech upgrades between waves.
- Reach higher waves to unlock all abilities.

## Project Structure

- `index.html`: Entire game (HTML, CSS, and JavaScript)

## Publish on GitHub

1. Create a new empty GitHub repository.
2. Run:

```bash
git remote add origin <your-repo-url>
git branch -M main
git push -u origin main
```

If you want to host it with GitHub Pages:

- In GitHub repo settings, enable Pages from the `main` branch root.
- Your game will be served at `https://<username>.github.io/<repo-name>/`.
