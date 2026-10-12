# TienditaPropia-stores

Deploy de GitHub Pages **sin** custom domain (sin `CNAME` de Citroleaf).

El workflow hace checkout de [`TienditaPropia1`](https://github.com/victorch2023/TienditaPropia1), elimina `public/CNAME` si existiera, construye y publica en Pages.

## URL Piyukis (sin Citroleaf)

https://victorch2023.github.io/TienditaPropia-stores/s/piyukis

Piyukis **no** tiene CNAME ni dominio propio: solo esta URL de GitHub Pages.

El repo principal `TienditaPropia1` mantiene `public/CNAME` = `www.citroleaf.com` y no debe usarse para enlaces `github.io` (redirige a citroleaf). En el host Citroleaf también funciona `https://www.citroleaf.com/s/piyukis`.
