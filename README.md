# New Safes — assets das landing pages

Imagens servidas por CDN para as LPs da New Safes publicadas no GreatPages.

Cada LP tem sua pasta. Os links usam o jsDelivr apontando para uma tag fixa,
para que uma atualização do repositório nunca altere uma LP já publicada:

```
https://cdn.jsdelivr.net/gh/BrunoFreitas-V4/newsafes-lp-assets@<tag>/<pasta>/<arquivo>
```

| Pasta | LP |
|---|---|
| `v1-cofres-e-portas/` | lp.newsafes.com.br/v1-cofres-e-portas |
| `v1-lp-antiga/` | LP V1 antiga (links fixados no SHA do commit, gerados por `greatpages/gerar-greatpages.py`) |

Para trocar uma imagem: suba o novo arquivo, crie uma tag nova e atualize os
links da LP para essa tag.
