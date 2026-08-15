# 🐠 Pixel Fishtank — Interactive Live Wallpaper

A detailed pixel-art aquarium that lives on your desktop. Everything is one
self-contained `index.html` — no build step, no dependencies, no network access,
no image files (every sprite is generated from pixel maps in the code).

## The fish react to you

- **Move your cursor** over the tank and nearby fish dart away from it.
  Get really close and they panic with a burst of speed.
- **Click anywhere** to drop a food pellet. It sinks with a wobble, and any
  fish that senses it races over and eats it (with a little gulp and a puff
  of crumbs). Uneaten pellets settle on the gravel and stay edible for a
  while before dissolving.

## What's in the tank

| Resident | Personality |
|---|---|
| Goldfish ×4 | Round-bodied mid-water cruisers with flowy double tails |
| Neon tetras ×8 | Tiny, quick, and they school together |
| Angelfish ×3 | Tall striped fins, slow and graceful |
| Clownfish ×4 | Stripey and darty |
| Plecos ×2 | Bottom-dwellers that hug the gravel and wait for food to sink |

Plus swaying kelp, a bubbling treasure chest, drifting light rays, rising
bubble vents, dust motes, and a dithered water gradient — all rendered at a
crisp ~480×270 internal resolution and upscaled pixel-perfect to any screen.

## Try it right now

Open `index.html` in any browser and press **F11** for fullscreen.

## Install as a live wallpaper

### Windows — Lively Wallpaper (free)

1. Install [Lively Wallpaper](https://www.rocksdanister.com/lively/) (free on the Microsoft Store).
2. In Lively, click **+ Add Wallpaper** and browse to `index.html`.
3. Right-click the wallpaper → **Customise**, and make sure mouse input is on
   (Settings → Performance → *Wallpaper input: On*) so the fish can see your cursor.

### Windows — Wallpaper Engine

1. In Wallpaper Engine, open the editor: **Wallpaper Editor → Create Wallpaper**,
   and select `index.html` (it imports as a web wallpaper).
2. Apply it. Under **Settings → General**, ensure mouse input for web wallpapers
   is enabled.

### macOS — Plash (free)

1. Install [Plash](https://sindresorhus.com/plash) from the Mac App Store.
2. Add a website and point it at the file, e.g. `file:///Users/you/fishtank/index.html`.
3. Enable **Browsing Mode** so clicks and cursor movement reach the tank.

### Linux

No single standard tool, but two easy options:

- Open `index.html` fullscreen in a browser on a spare workspace/monitor.
- Tools like [Komorebi](https://github.com/cheesecakeufo/komorebi) or a
  borderless browser window layered behind your desktop icons work too.

## Tweak it

Open `index.html` and edit the `CONFIG` object at the top of the script:
fish counts per species, flee radius, food sensing range, pellet lifetime,
plant density, and the internal resolution are all right there.
