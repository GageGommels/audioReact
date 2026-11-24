# audioReact

Microphone-driven visuals that run in the browser, made for casting to a TV.
One file, no dependencies, no build step.

## Scenes

- **Galaxy** – a flight through a star field; bass sets the speed, beats kick it into warp
- **Pulsar** – a radial spectrum with a waveform core and beat shockwaves
- **Aurora** – layered ribbons shaped by the spectrum
- **Bloom** – kaleidoscopic particle bursts

## Run it

Browsers only allow microphone access on `https://` or `localhost`:

    python3 -m http.server 8000   # then open http://localhost:8000

Or host it with GitHub Pages (Settings → Pages → deploy from a branch).

## Cast it

In Chrome or Edge: menu (⋮) → Cast, save and share → Cast… → pick the TV, source **Tab**.
On Apple devices use Screen Mirroring. Then press `F` for fullscreen.

Keys: `1`–`4` scene · `←` `→` previous/next · `A` auto-cycle · `F` fullscreen
