# BlastyBubs — WebGL production build (GameBull)

Production deploy of the BlastyBubs WebGL build, served via GitHub Pages.

- **Play:** https://alishehroz-ideo.github.io/blastybubs/
- Unity 6000.4.3f1 · WebGL · IdeofuzionBridge template · 1080x1920 portrait
- GameBull API: `https://api.g-b.store`
- GameBull lobby canvas lives in `scn_boot` (DontDestroyOnLoad), shows in `scn_game`.
- Single-scene gameplay: `gameplaySceneName` is empty; runs start via `onStartSolo`.
- Score submission + game-end panel via `GameBullBlastyBridge`.
