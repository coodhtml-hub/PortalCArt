# Portal do Estudante CART - Heroku

Projeto estático servido por Node.js para hospedagem no Heroku. Todos os arquivos ficam diretamente na raiz desta pasta, sem subpastas.

## Arquivos

- `index.html`: textos e conteúdo do portal, escritos diretamente em HTML.
- `orientacoes-academicas.html` e `historia-if.html`: textos das páginas secundárias.
- `styles.css`, `orientacoes.css`, `historia.css`: estilos visuais separados.
- `script.js`: busca e menu móvel; os textos não são montados por JavaScript.
- Imagens: ficam no mesmo nível dos códigos.
- `server.js`, `package.json` e `Procfile`: inicialização no Heroku.

Envie o conteúdo desta pasta para a raiz do app. O `Procfile` inicia `server.js`, que entrega páginas, CSS, JavaScript e imagens.

O botão do Manual aponta para `manual-do-estudante.pdf`; coloque esse arquivo na raiz quando estiver pronto. O PDF/link do calendário ainda não foi fornecido.
