# takitani.dev — portfolio

Single-page portfolio. HTML + CSS + JS, sem framework, sem build.

## Rodar

Abra `index.html` no navegador, ou:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Deploy (GitHub Pages)

Push pro repo `Rafatakitani.github.io` (branch `main`) — Pages serve o `index.html` na raiz automaticamente.

## Editar projetos

Listas em dois arrays no `<script>` do `index.html`: `work` (ledger) e `more` (grid). Cada item é `{n/t, d, t, y, u}`.
