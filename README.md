# Portal de Metas — Fiscaltech 2026

Tela única consolidando as metas de todas as áreas sob responsabilidade (Produção, MI, Estoque, Logística), com nível N1–N4 conforme a Matriz de Metas 2026.

- Sem build, sem backend — um único `index.html` estático.
- O card **Aderência à Programação** busca dado ao vivo direto da planilha oficial de produção (via Apps Script de leitura), a mesma fonte usada pelo [Cronograma de Produção](https://cronograma-producao-psi.vercel.app/).
- Os demais cards (Estoque Manutenção, Acuracidade do Estoque, Ruptura de Estoque, SLA de Atendimento) ficam como "aguardando conexão" até as planilhas de origem de cada área serem conectadas do mesmo jeito.

## Publicar

1. Suba este repositório no GitHub (arquivo `index.html` na raiz).
2. Conecte o repositório na [Vercel](https://vercel.com) (ou Netlify/GitHub Pages) — nenhuma configuração de build é necessária, é só apontar pra raiz.
3. Pronto: a cada `git push`, o site atualiza sozinho.
