# Savio Financeiro

Dashboard web para visualizar e organizar um relatório de distribuição de comissões, com filtros, indicadores e gráficos.

> Projeto de portfólio em HTML e JavaScript. É uma demonstração de interface e manipulação de dados no navegador; não use para administrar dados financeiros reais.

## Funcionalidades

- Indicadores de receitas, comissões, premiações e valores líquidos.
- Tabela de grupos com filtros para totais positivos e negativos.
- Gráficos para resumir os dados.
- Edição de grupos, indicações, período e despesas.
- Exportação dos dados para JSON.
- Persistência local no navegador por meio de `localStorage`.

## Tecnologias

- HTML5
- JavaScript
- Tailwind CSS via CDN
- Chart.js
- Font Awesome

## Como executar

1. Clone este repositório.
2. Abra `index.html` em um navegador com acesso à internet para carregar as bibliotecas externas.

## Limitações da demonstração

- Os dados ficam no navegador e não são sincronizados entre dispositivos.
- O controle de acesso ocorre no cliente e não substitui autenticação de servidor.
- Não há banco de dados, API ou controle de acesso por usuário.
- Revise e substitua os dados de exemplo antes de apresentar ou compartilhar capturas de tela.

## Próximos passos

- Separar dados e interface e criar uma API com autenticação real.
- Validar entradas e proteger informações financeiras no servidor.
- Adicionar testes automatizados e documentar a implantação.
