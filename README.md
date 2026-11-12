# Observatório TJRS — Dashboard interativo

Site estático pronto para GitHub + Cloudflare Pages. Não exige Node.js, npm, terminal ou compilação.

## Publicação
1. Crie um repositório no GitHub e envie o conteúdo extraído deste ZIP (o arquivo `index.html` deve ficar na raiz).
2. Na Cloudflare, abra **Workers & Pages** e crie um projeto **Pages** conectado ao repositório GitHub.
3. Configure **Framework preset: None**, **Build command: (vazio)**, **Build output directory: /** (raiz).
4. Publique. A Cloudflare disponibilizará um endereço `.pages.dev`.

## Observações
- Este pacote usa a versão HTML independente do painel interativo, não o código-fonte React. Isso elimina a etapa de compilação e torna a publicação direta.
- O dashboard inclui dados de movimentação e pode expor nomes de servidores; revise antes de tornar público.
- Os índices são condicionais às limitações de dados documentadas no painel.
