# -e-commerce-EvoWear

Projeto

# EvoWear — landing page de e-commerce

Página estática de uma loja fictícia de moda esportiva. O projeto apresenta uma vitrine inicial com navegação, banner principal, categorias de produtos, mosaico visual e rodapé com newsletter e redes sociais.

> Este é um projeto de interface. Os links, o carrinho e o formulário de newsletter são visuais e ainda não possuem integração com um back-end.

## Tecnologias utilizadas

- **HTML5** — estrutura semântica da página: cabeçalho, navegação, conteúdo principal, seções e rodapé.
- **CSS3** — estilização, cores, tipografia, animações de hover e responsividade.
- **Flexbox** — alinhamento do cabeçalho, categorias, botões, links e conteúdo do rodapé.
- **CSS Grid** — composição do mosaico de produtos em diferentes tamanhos de tela.
- **Google Fonts** — carregamento da fonte Ubuntu.

Não foram utilizados JavaScript, frameworks, bibliotecas ou gerenciadores de dependência.

## Estrutura do projeto

```text
e-commerce-sytnyaxwaet/
├── index.html                  # Estrutura da página
├── css/
│   ├── reset.css               # Normalização de estilos entre navegadores
│   ├── variables.css           # Fonte principal e variáveis globais
│   ├── base.css                # Estilos reutilizáveis, como botões
│   └── components/             # Estilos por seção
│       ├── header.css
│       ├── hero.css
│       ├── product-categorias.css
│       ├── product-grid.css
│       └── footer.css
└── images/                     # Logo, ícones, banners e imagens de produtos
```

## Como executar

1. Baixe ou clone este repositório.
2. Abra a pasta do projeto no seu editor de código.
3. Abra o arquivo `index.html` no navegador.


## Como a página foi construída

1. O `header` mantém a marca e os links de navegação no topo da tela.
2. A seção `hero` usa uma imagem de fundo, texto de destaque e botões de chamada para ação.
3. A seção de categorias apresenta Top, Camisa, Short e Calça em cards com sobreposição escura para melhorar a leitura.
4. O grid de produtos usa áreas nomeadas do CSS Grid para criar um mosaico assimétrico no desktop.
5. O rodapé concentra newsletter, redes sociais e links institucionais.

## Responsividade

A interface foi adaptada com media queries para manter a leitura e a navegação em telas menores.

| Faixa de tela | Comportamento |
| --- | --- |
| Acima de `1000px` | Cabeçalho completo, categorias lado a lado e mosaico de produtos com quatro colunas. |
| Até `1000px` | Espaçamentos e tipografia do cabeçalho diminuem; categorias ocupam duas colunas; grid de produtos passa para duas colunas. |
| Até `700px` | Menu de navegação é recolhido e aberto pelo ícone hamburger; botões ficam menores; categorias são empilhadas; mosaico passa para uma coluna. |

### Detalhes técnicos da responsividade

- O menu mobile é controlado por um `input` do tipo checkbox e CSS, sem JavaScript.
- As categorias usam `flex-wrap` no tablet e `flex-direction: column` no celular.
- O mosaico usa `grid-template-areas`: quatro colunas no desktop, duas no tablet e uma no celular.
- Imagens usam `background-size: cover` para ocupar os cards sem distorção.
- O reset inclui `prefers-reduced-motion`, reduzindo animações para pessoas que preferem menos movimento.

## Autor

Projeto desenvolvido como prática de HTML e CSS do curso.# E-commerce-Evoxwaet
