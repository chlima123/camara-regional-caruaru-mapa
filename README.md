# Mapa da competência territorial — Câmara Regional de Caruaru (TJPE)

Dashboard single-file (`index.html`, Leaflet + malha municipal do IBGE) com os **78 municípios**
(68 comarcas + 10 termos judiciários) das **8 circunscrições** da Câmara Regional de Caruaru
(7ª, 8ª, 9ª, 10ª, 11ª, 12ª, 14ª e 19ª).

## Links

- **Vercel (principal):** https://camara-regional-caruaru-mapa.vercel.app
- **GitHub Pages (espelho):** https://chlima123.github.io/camara-regional-caruaru-mapa/

Os dois servem o **mesmo byte a byte** (SHA-1 `99d1099bd54ef008987ea0ff42633fe6256d451d`).
Público, sem senha.

## Conteúdo

- Mapa: 184 polígonos (PE inteira); os 78 da competência pintados por circunscrição, o resto em cinza.
- Filtro por circunscrição (contador "N de 78 municípios"), busca sem acento por município/comarca.
- Ficha do município: comarca, termo, população (Censo 2022).
- 8 cards com todas as comarcas de cada circunscrição.
- Botão "Mapa base": liga/desliga o CARTO light (sem chave de API).

## Fontes

Anexo I do COJE (LC 100/2007, red. LC 452/2021) + art. 78 do RI/TJPE; malha e população do IBGE (Censo 2022).

## Publicação

Deploy pelo upload direto da API da Vercel (`~/.hermes/skills/.../deploy_vercel_static.py`);
o projeto Vercel `camara-regional-caruaru-mapa` (`prj_JrxraKySXvCmmDZzi4EWQCsOqAQ3`) é público
(`ssoProtection`/`passwordProtection` nulos). `.vercel/` fica fora do git.
