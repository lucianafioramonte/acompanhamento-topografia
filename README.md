# Acompanhamento de Topografia — Comparativo de Terraplanagem

Dashboard estático (HTML único, sem backend) com o comparativo de volumes de terraplanagem
(previsto x executado x saldo) por trecho/medição, baseado nos levantamentos topográficos.

## Estrutura
- `index.html` — dashboard publicado (também disponível como `comparativo_terraplanagem.html`)

## Como atualizar
O histórico de medições fica embutido no próprio HTML (`EMBEDDED_HISTORY`). Para adicionar uma
nova medição, envie a planilha `.xlsx` (aba **RESUMO DE VOLUMES**, colunas L:O) para quem mantém
este projeto, que irá gerar uma nova versão do `index.html` com os dados atualizados.

## Publicação (GitHub Pages)
Ative em *Settings → Pages → Branch: main → / (root)* para publicar o `index.html` como página web.
