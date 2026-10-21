# IA sem mistério

Trilha gamificada para aprender IA, LLMs, prompts, agentes, MCP e RAG, explicada com a metáfora de uma confeitaria.

É uma página estática: um único `index.html`, sem build e sem dependências (só as fontes do Google Fonts, carregadas pela internet).

## Publicar no GitHub Pages

1. Coloque estes arquivos na raiz do repositório (ou numa pasta `docs/`).
2. No GitHub: **Settings → Pages → Build and deployment**.
3. Em **Source**, escolha **Deploy from a branch**, selecione a branch (por exemplo `main`) e a pasta (`/ (root)` ou `/docs`) e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Rodar localmente

Abra o `index.html` no navegador. Se preferir um servidor local: `python3 -m http.server` e acesse http://localhost:8000.

## Observações

- O progresso (paradas concluídas e hábitos marcados) fica salvo no `localStorage` do navegador. O botão "Zerar meu progresso" fica no rodapé.
- O chat "Pergunte ao Bit" só funciona dentro do Claude e fica oculto nesta versão. As perguntas frequentes continuam funcionando.
- As simulações usam números e receitas inventados, só para ilustrar as ideias.
