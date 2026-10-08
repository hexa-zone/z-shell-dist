# z-shell

[Français](#français) | [English](#english)

## Français

Simulateur Linux dans le navigateur pour les exercices de formation. Version en ligne : https://shell.hexa.zone

### Exécution locale

Extrayez `z-shell-v1.0.zip`, ouvrez un terminal dans le répertoire extrait, puis lancez :

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Ouvrez http://localhost:8080. N’ouvrez pas directement `index.html` avec `file://`.
Le fichier `index.html` et le répertoire `assets/` du dépôt peuvent également être
servis par tout serveur HTTP statique. Conservez-les ensemble. Les fichiers et
sessions simulés sont enregistrés dans le navigateur, séparément pour chaque
adresse de site.

Distribué sous licence MIT ; voir `LICENSE`.
Les composants tiers conservent leurs licences respectives ; voir `THIRD-PARTY-NOTICES.txt`.

## English

Browser-based Linux training simulator. Online: https://shell.hexa.zone

### Run locally

Extract `z-shell-v1.0.zip`, open a terminal in the extracted directory, then run:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://localhost:8080. Do not open `index.html` directly with `file://`.
The repository's `index.html` and `assets/` can also be served by any static
HTTP server. Keep them together. Simulated files and sessions are stored in
the browser, separately for each site address.

Licensed under the MIT License; see `LICENSE`.
Third-party components retain their respective licences; see `THIRD-PARTY-NOTICES.txt`.
