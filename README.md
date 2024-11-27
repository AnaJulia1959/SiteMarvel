# SiteMarvel

Este projeto consiste em um site da Marvel desenvolvido como parte da disciplina **Programação Web I**. O site apresenta um layout moderno, estilizado com CSS, e foi dockerizado para facilitar sua execução em qualquer ambiente.

## 🚀 Funcionalidades

- **Menu de Navegação**: Uma barra de menu com borda inferior estilizada.
- **Seção de Lançamentos**: Apresenta imagens e informações de novos quadrinhos e filmes.
- **Seção de Notícias (News)**: Inclui destaques com imagens e textos sobre novidades do universo Marvel.
- **Rodapé**: Com design estilizado e informações sobre o site.

## 🎨 Estilização

- **Estilização Global**:
  - Margem zero para todos os elementos (`*`).
  - Fundo preto (`black`), fonte branca (`white`) e estilo de texto em maiúsculas com a fonte "Courier New".
  
- **Menu**:
  - Margem superior e inferior: `20px`.
  - Borda inferior: `1px` sólida e branca.
  
- **Imagem Principal**:
  - Largura ajustada para ocupar 100% da tela.

- **Seção de Lançamentos**:
  - Margem superior: `20px`.
  - Fundo com gradiente de preto (`black`) para cinza escuro (`#202020`).
  - Imagens com largura de `60%`.
  - Distância do conteúdo para a borda inferior: `4%`.

- **Seção de Notícias**:
  - Fundo do título e da seção: `#202020`.
  - Imagens com largura de `80%`.
  - Espaçamento interno (padding) de `10px` em todos os lados da seção.
  - Texto alinhado à esquerda, com espaçamento superior de `4%`.

- **Rodapé**:
  - Fundo cinza escuro (`#202020`).
  - Fonte em negrito.
  - Espaçamento interno (padding) de `20px`.

## 🐳 Dockerização

Este site foi configurado para rodar em um ambiente Docker utilizando o servidor web **Nginx**.

