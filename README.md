# Organizador Financeiro Pessoal

MVP funcional baseado na planilha `planejamento_quinzenal_2026.xlsx`.

## Como executar

Opção mais simples:
1. Abra `index.html` em um navegador moderno.

Para servir localmente por HTTP (recomendado):
1. Abra um terminal na pasta.
2. Execute `python -m http.server 8080`.
3. Acesse `http://localhost:8080`.

## O que já funciona

- Dados iniciais importados da planilha de julho a dezembro/2026.
- Saldo encadeado entre quinzenas.
- Edição de receitas e despesas.
- Inclusão e exclusão de despesas.
- Projeção automática de saldo.
- Dashboard com indicadores e gráfico.
- Busca e filtros.
- Persistência local no navegador.
- Exportação e importação de backup em JSON.
- Restauração dos dados originais da planilha.

## Observação

Esta versão é um MVP local, sem login e sem banco de dados remoto. Os dados são persistidos no `localStorage` do navegador.
