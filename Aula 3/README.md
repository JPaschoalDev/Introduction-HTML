# Aula 3 - Site Institucional: PowerFit Academia

Site institucional fictício de uma academia, desenvolvido com **HTML e CSS puros** (com um toque leve de JavaScript apenas para o efeito de sombra no header), atendendo a todos os requisitos da atividade e a todos os desafios extras.

## 📁 Estrutura

```
Aula 3/
├── index.html                # Página inicial
├── README.md
├── Pages/
│   ├── sobre.html             # Página Sobre
│   ├── servicos.html          # Página de Serviços (com cards)
│   └── contato.html           # Página de Contato (desafio extra)
├── Styles/
│   └── style.css              # Estilização geral do site
└── images/
    ├── favicon.png
    ├── hero.jpg
    ├── sobre.jpg
    ├── servico-musculacao.jpg
    ├── servico-crossfit.jpg
    ├── servico-zumba.jpg
    └── servico-personal.jpg
```

> ℹ️ As imagens de conteúdo são **placeholders** gerados automaticamente. Substitua os arquivos dentro de `images/` pelas fotos reais desejadas, mantendo os mesmos nomes.

## ✅ Requisitos atendidos

- **4 páginas:** Início, Sobre, Serviços e Contato, todas com menu de navegação funcional.
- **Página Inicial:** nome do negócio, imagem, texto de apresentação e menu.
- **Sobre:** texto explicativo, imagem e seção extra de diferenciais da academia.
- **Serviços:** 4 serviços (Musculação, Crossfit, Zumba, Personal Trainer) em cards, cada um com nome, descrição e imagem.
- **CSS:** cores personalizadas, tamanhos de fonte variados, espaçamento entre elementos, bordas arredondadas, cabeçalho estilizado, menu estilizado e organização visual com `main`/`section`.
- **Sem formulários, sem banco de dados** — conforme as regras da atividade.

## ⭐ Desafios extras atendidos

| Desafio | Onde foi implementado |
|---|---|
| Página **Contato** com endereço, telefone e redes sociais | `Pages/contato.html` |
| Efeitos **:hover** no menu e nos cards | `style.css` |
| **Cards** para os serviços | `Pages/servicos.html` + `style.css` (grid responsivo) |
| **display: flex / grid** para organizar elementos | Usado no header, nav, `.sobre-conteudo`, `.cards` e `.contato-grid` |

## ✨ Polimento visual adicional

- **Favicon** personalizado na aba do navegador.
- **Fade-in** suave ao carregar cada página.
- **Sombra dinâmica no header** ao rolar a página (pequeno script JS).
- Header fixo (`sticky`) durante a rolagem.
- Seção de diferenciais na página Sobre e coluna extra na página Contato, para melhor aproveitamento do espaço.

## 🛠️ Tecnologias

- HTML5
- CSS3 (Flexbox, Grid, transições, animações, media query para responsividade)
- JavaScript (apenas o efeito de sombra no header ao rolar)
- Font Awesome (ícones das redes sociais e dos diferenciais)

## ▶️ Como visualizar

Abra `index.html` em qualquer navegador (recomendado usar a extensão **Live Server** do VS Code). A navegação entre as páginas funciona pelo menu, presente em todas elas.