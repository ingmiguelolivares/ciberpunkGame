# Cyberpunk Game WebGL build

This folder is a static Unity WebGL build prepared for GitHub Pages without Git LFS.

The Unity data archive is split into `Build/ciberpunk.data.gz.part-*` files, each
below GitHub's 100 MB regular-file limit. `index.html` downloads the parts and
reassembles them in memory before starting Unity. Keep all parts together when
publishing the repository.

The first scene in the Unity build is `Start`, followed by `NextRace`, the four
tracks, `Podium`, `WinScene`, `LoseScene`, and `Creditos`.
