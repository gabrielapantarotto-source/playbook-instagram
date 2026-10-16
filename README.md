# Playbook de Instagram | hoff.food

Página estática, sem build. Para publicar no GitHub Pages:

1. Crie um repositório (ex.: `playbook`) e envie TODOS os arquivos desta pasta para a raiz dele.
2. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
3. O endereço é `https://playbook.estudiohoff.com.br/`. No DNS do domínio estudiohoff.com.br, crie um registro CNAME com nome `playbook` apontando para `gabrielapantarotto-source.github.io`. Em Settings > Pages, confirme o domínio personalizado e marque "Enforce HTTPS".
4. Se o endereço mudar, troque `https://playbook.estudiohoff.com.br/` pelo endereço real em `index.html` (4 linhas: canonical, og:url, og:image e twitter:image).

Arquivos:
- index.html: a página, com as tags da prévia de link.
- og-image.png: imagem da prévia (1200x630).
- favicon.ico, favicon-16x16.png, favicon-32x32.png, favicon-48x48.png, apple-touch-icon.png, icon-192.png, icon-512.png, site.webmanifest: ícone com fundo tomate.
- CNAME: diz ao GitHub Pages qual é o domínio personalizado.
- .nojekyll: evita que o GitHub processe a pasta.

Se trocar a imagem da prévia depois, o WhatsApp guarda a antiga em cache. Para forçar a atualização, renomeie o arquivo (ex.: og-image-2.png) e ajuste as 2 linhas que o citam.
