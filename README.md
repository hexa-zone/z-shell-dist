# h-term

[![Démo en ligne](https://img.shields.io/badge/D%C3%A9mo-en%20ligne-blue)](https://shell.hexa.zone)
[![Licence MIT](https://img.shields.io/badge/Licence-MIT-green)](LICENSE)

[Français](#français) | [English](#english)

## Français

h-term (hexa-term) remplace le nom z-shell pour éviter la confusion avec le shell Unix zsh.

Simulateur Linux dans le navigateur pour les exercices de formation. Version en ligne : https://shell.hexa.zone

### Exécution locale

Extrayez `h-term-v1.0.zip`, ouvrez un terminal dans le répertoire extrait, puis lancez :

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Ouvrez http://localhost:8080. N’ouvrez pas directement `index.html` avec `file://`.
Le fichier `index.html` et le répertoire `assets/` du dépôt peuvent également être
servis par tout serveur HTTP statique. Conservez-les ensemble. Les fichiers et
sessions simulés sont enregistrés dans le navigateur, séparément pour chaque
adresse de site.

Après une mise à jour de h-term, rechargez la page pour charger la nouvelle
version. Il peut ensuite être nécessaire d’exécuter `reset-world` pour bénéficier
des dernières fonctionnalités qui dépendent de l’état initial du monde simulé.
**Attention : cette commande réinitialise tous les hôtes virtuels, leurs fichiers,
les services et la topologie ; vos modifications et votre progression dans les
labs sont perdues.** Exportez d’abord les données à conserver avec `export-lab`.
`reset-world` ne télécharge pas une nouvelle version de l’application.

Distribué sous licence MIT ; voir `LICENSE`.
Les composants tiers conservent leurs licences respectives ; voir `THIRD-PARTY-NOTICES.txt`.

## English

h-term (hexa-term) replaces the name z-shell to avoid confusion with the Unix shell zsh.

Browser-based Linux training simulator. Online: https://shell.hexa.zone

### Run locally

Extract `h-term-v1.0.zip`, open a terminal in the extracted directory, then run:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://localhost:8080. Do not open `index.html` directly with `file://`.
The repository's `index.html` and `assets/` can also be served by any static
HTTP server. Keep them together. Simulated files and sessions are stored in
the browser, separately for each site address.

After updating h-term, reload the page to load the new version. You may then
need to run `reset-world` to benefit from the latest features that depend on the
simulated world's initial state. **This command resets all virtual hosts, their
files, services and topology; your changes and lab progress will be lost.**
Export any data you need to keep with `export-lab` first. `reset-world` does not
download a new version of the application.

Licensed under the MIT License; see `LICENSE`.
Third-party components retain their respective licences; see `THIRD-PARTY-NOTICES.txt`.
