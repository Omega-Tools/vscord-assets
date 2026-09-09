# vscord-assets

Images publiques servies à Discord pour la présence VS Code du fork
[vscord Omega](https://github.com/Omega-Tools/Vscode_Rich_Presence).

Discord télécharge les images de rich presence de façon anonyme : elles doivent donc vivre dans un
dépôt public. Ce dépôt ne contient que des logos d'éditeurs, rien d'autre.

## icons/flat

Logos d'éditeurs détourés — fond transparent, artwork recadré pour remplir la tuile, 1024×1024.
Générés depuis les assets d'upstream par `scripts/flatten-editor-icons.py` dans le dépôt du fork.

Utilisés comme grande image de la présence :

```
https://raw.githubusercontent.com/Omega-Tools/vscord-assets/main/icons/flat/{app_id}.png
```

où `{app_id}` vaut `vscode`, `vscode-insiders`, `vscodium`, `vscodium-insiders`, `cursor` ou
`antigravity`.
