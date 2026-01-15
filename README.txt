Flashcards — Autorregulação (mobile-first, arquivo único)

O que tem aqui:
- index.html  (tudo embutido, sem dependências externas)

Como rodar local:
- Abra index.html no navegador (celular ou desktop).

Cloudflare Workers (jeito simples):
- Você pode servir este index.html como "Static Assets" (Workers) ou usar Pages.
- O arquivo está com ~0,8 MB, então cabe com folga no limite de arquivo por asset (25 MiB) e tende a caber também no limite de bundle do Worker, se você optar por embutir.

Controles:
- Toque: vira a carta
- Swipe para esquerda/direita: próxima/anterior
- Slider no topo: pular para carta
- Teclado: ← →, Espaço/Enter (virar), R (aleatória), S (embaralhar)

Obs:
- As artes originais eram SVG pesados; aqui elas foram rasterizadas para WebP (mantendo o visual) para ficar leve e estável em mobile/Workers.
