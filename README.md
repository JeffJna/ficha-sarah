# ficha-sarah

Site estatico em HTML para publicar no GitHub Pages, agora com estrutura PWA no mesmo padrao do projeto de referencia.

## Arquivos principais
- `index.html`: pagina principal publicada com metadados PWA.
- `manifest.json`: configuracao de instalacao do app.
- `sw.js`: service worker para cache basico offline.
- `icons/`: icones do aplicativo derivados da arte base.
- `remixed-782c0b86.html`: versao original mantida como backup.

## Como publicar no GitHub
1. Faca push para o branch `main`.
2. No GitHub, abra **Settings > Pages** e confirme **Source: GitHub Actions**.
3. Aguarde a workflow `Deploy static HTML to GitHub Pages` finalizar.
4. O site sera publicado na URL de Pages do repositorio.

## Desenvolvimento local
Abra o `index.html` direto no navegador ou use um servidor estatico simples para validar a instalacao do PWA e o service worker.
