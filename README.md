# Spiget ID Search

Site minimalista para pesquisar plugins no [Spiget](https://spiget.org) pelo **nome** e copiar o **Resource ID** (útil para Minepanel / `SPIGET_RESOURCES`).

## Funcionalidades

- Sugestões em tempo real enquanto digitas (API Spiget)
- Debounce + cancelamento de pedidos antigos (mais rápido e leve)
- Um clique para copiar o ID
- Link direto para a página no SpigotMC
- Layout responsivo (telemóvel e desktop)

## Usar online (GitHub Pages)

1. No repositório: **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / pasta `/ (root)`
4. Abre: `https://vini2191.github.io/spiget-id-search/`

## Usar localmente

```bash
# na pasta do projeto
python3 -m http.server 8080
# ou: npx serve .
```

Abre http://localhost:8080

> Não abras o `index.html` com `file://` — o browser bloqueia o `fetch` à API.

## Exemplo

| Plugin     | ID    |
|------------|-------|
| LuckPerms  | 28140 |
| Vault      | 34315 |
| ViaVersion | 19254 |

## Créditos

Dados fornecidos pela [Spiget API](https://api.spiget.org).
