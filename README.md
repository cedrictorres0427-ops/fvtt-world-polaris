# Polaris

Monde Foundry VTT `polaris`, système `polaris`.

## Installation

Dans Foundry : **Mondes** → **Installer** → coller ce lien dans « URL du manifeste » :

```
https://github.com/cedrictorres0427-ops/fvtt-world-polaris/releases/latest/download/world.json
```

## Publier une nouvelle version

1. Augmenter `version` dans `world.json` et remplacer la version dans `download`.
2. Commit, puis tag `v<version>` poussé sur GitHub : l'action « Release » construit le zip et la release.
