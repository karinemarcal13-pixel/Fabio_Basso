# Farmácia · Controle de Estoque

Sistema de controle de estoque para farmácia, em um único arquivo HTML (sem instalação e sem servidor).

## Funcionalidades

- Painel com total de produtos, unidades, valor em custo e em venda, alertas de estoque baixo e últimas movimentações
- Cadastro de produtos (código, nome, categoria, fornecedor, preços, estoque mínimo e quantidade)
- Busca e filtros por categoria e status
- Movimentações de entrada, saída e ajuste, com histórico e saldo
- Cadastro de categorias e fornecedores
- Exportação em CSV, backup e restauração em JSON
- 100 produtos de exemplo para teste

## Como usar

Abra o arquivo `index.html` no navegador. Os dados ficam salvos no próprio navegador (localStorage).
Para começar do zero, vá na aba Dados e clique em Apagar tudo.

## Publicar com GitHub Pages

1. No repositório, abra Settings e depois Pages
2. Em Source, escolha Deploy from a branch
3. Selecione a branch `main` e a pasta `/ (root)` e salve
4. O site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`
