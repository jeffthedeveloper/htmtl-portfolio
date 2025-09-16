# HTML Portfolio (htmtl-portfolio)

Este repositório contém um projeto de portfólio pessoal simples, desenvolvido inteiramente em HTML. O projeto serve como uma página de entrada (`index.html`) que apresenta o desenvolvedor e fornece links para subpáginas, incluindo projetos de exemplo e informações de contato.

O `index.html` está estruturado como um exercício ("TODOs") para construir um portfólio.

## Funcionalidades

  * **Página Principal (`index.html`):** Apresenta o desenvolvedor (Jefferson Firmino Mendes, web developer).
  * **Projetos de Exemplo:** Inclui os arquivos HTML para dois projetos de exemplo:
      * **Ranking de Filmes** (`public/movie-ranking.html`).
      * **Convite de Aniversário** (`public/birthday-invite.html`).
  * **Previews de Imagem:** A página principal exibe screenshots dos projetos de exemplo.
  * **Páginas de Navegação:**
      * **Sobre Mim (`public/about.html`):** Uma página com texto placeholder *Lorem Ipsum*.
      * **Contato (`public/contact.html`):** Uma página com informações de contato placeholder.

## Estrutura do Repositório

```
/
│
├── index.html              # A página principal do portfólio
├── README.md               # Este arquivo
├── goal.png                # Imagem do objetivo final do exercício
├── solution.html           # Arquivo de solução do exercício
│
├── assets/
│   └── images/
│       ├── birthday-invite.png # Preview do projeto de convite
│       └── movie-ranking.png # Preview do projeto de filmes
│
└── public/
    ├── about.html          # Página "Sobre Mim"
    ├── contact.html        # Página de "Contato"
    ├── birthday-invite.html  # O projeto de convite de aniversário
    └── movie-ranking.html  # O projeto de ranking de filmes
```

## Como Usar

Por ser um projeto estático (apenas HTML), não é necessário um servidor.

1.  **Clone ou baixe o repositório.**
2.  **Abra o arquivo `index.html`** diretamente no seu navegador web preferido para visualizar o portfólio.
3.  Você pode navegar para as outras páginas clicando nos links "Sobre Mim" e "Contatos".

## Observações

  * **Projeto de Estudo:** O `index.html` contém vários comentários \`\`, indicando que é um projeto em desenvolvimento ou um exercício de um curso de desenvolvimento web.
  * **Conteúdo Placeholder:** As páginas `about.html` e `contact.html` ainda não foram personalizadas e contêm texto genérico.
  * **Links de Projeto:** Os links para os projetos na página `index.html` não estão totalmente implementados; eles exibem as imagens, mas não vinculam as imagens aos respectivos arquivos HTML dos projetos (como `public/movie-ranking.html`).
