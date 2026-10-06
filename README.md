# z-shell

Browser-based Linux training simulator. Online: https://shell.hexa.zone

## Run locally

Extract `z-shell-v1.0.zip`, open a terminal in the extracted directory, then run:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://localhost:8080. Do not open `index.html` directly with `file://`.
The repository's `index.html` and `assets/` can also be served by any static
HTTP server. Keep them together. Simulated files and sessions are stored in
the browser, separately for each site address.

Third-party licence notices are in `THIRD-PARTY-NOTICES.txt`.
