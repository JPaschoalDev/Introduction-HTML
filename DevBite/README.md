# DevBite

Interface web de um sistema de pedidos para a **DevBite**, uma lanchonete voltada para profissionais de tecnologia.

Nesta etapa foi desenvolvida apenas a parte visual (HTML5 e CSS3). O back-end e a interatividade (JavaScript) serão feitos na próxima etapa.

## Tecnologias

- HTML5
- CSS3 (Flexbox e CSS Grid)

## Estrutura do projeto

```
DevBite/
├── index.html
├── checkout.html
├── admin.html
├── css/
│   └── style.css
├── img/
│   └── (imagens dos produtos)
└── README.md
```

## Telas

### Cardápio (`index.html`)
- Cabeçalho com logo e menu de navegação (Cardápio, Meu Carrinho e Área Restrita)
- Barra lateral com as categorias: Burgers, Bebidas e Sobremesas
- Grade de produtos com imagem, nome, preço e botão "Adicionar ao Carrinho"

### Finalização de Pedido (`checkout.html`)
- Mesmo menu de navegação da página inicial
- Tabela do carrinho com produto, preço unitário, quantidade, subtotal e botão de remover
- Valor total do pedido
- Formulário de entrega e pagamento (nome, endereço, telefone e método de pagamento)

### Painel Administrativo (`admin.html`)
- Menu administrativo com Dashboard, Cadastrar Produto e Relatórios
- Formulário de cadastro de produto (nome, descrição, preço, categoria e imagem)
- Tabela com os 3 pedidos mais recentes e o status de cada um

## Preparação para o JavaScript

- Os botões, formulários e tabelas possuem `id` único
- Os botões de "Adicionar ao Carrinho" e "Remover" também têm o atributo `data-id`
- Os campos dos formulários possuem `name` e `id`
- As classes são modulares: `.btn`, `.btn-primary`, `.btn-danger`, `.card-produto`

## Como executar

1. Baixe ou clone o projeto
2. Abra a pasta `DevBite` no IntelliJ
3. Clique com o botão direito no arquivo `index.html` e escolha **Open in → Browser**
4. Use o menu de navegação para acessar as outras telas

## Requisitos atendidos

- [x] Tags semânticas (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`)
- [x] Layout feito com Flexbox e Grid, sem `float` nem posicionamento absoluto
- [x] CSS separado em arquivo externo (`style.css`)
- [x] Três telas ligadas por menu de navegação
- [x] Layout responsivo (adapta ao redimensionar a janela)
- [x] Formulários com a tag `<form>` e inputs com `name` e `id`

## Autor

- Nome: João Victor Paschoal
- Curso: Análise e Desenvolvimento de Sistemas (SENAI - CTTI)