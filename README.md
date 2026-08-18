# Projeto Final - DankiCode

Landing page responsiva desenvolvida como projeto final do curso Frontend 2 da Danki Code. A página apresenta uma agência digital fictícia, seus diferenciais, benefícios, depoimentos e um formulário de contato.

## Demonstração

A versão publicada está disponível no GitHub Pages:

<https://lfbond.github.io/projetoFinal_cursoFrontEnd2_DankiCode/>

## Funcionalidades

- Navegação por âncoras entre as seções da página.
- Menu desktop e menu mobile com abertura e fechamento responsivos.
- Seção de apresentação com chamada para ação.
- Exibição de marcas e benefícios da agência.
- Carrossel automático de depoimentos com navegação adaptada para telas menores.
- Formulário visual de contato.
- Layout responsivo para desktops, tablets e celulares.

## Tecnologias e bibliotecas

- **HTML5** para a estrutura semântica da página.
- **CSS3** para layout, cores, tipografia, imagens de fundo e responsividade.
- **JavaScript** para os comportamentos da interface.
- **jQuery** para manipulação do DOM e eventos do menu mobile.
- **Slick Carousel** para o carrossel de depoimentos.
- **Font Awesome** e **Google Fonts** carregados por CDN no HTML.

O projeto não utiliza React, Node.js, gerenciador de pacotes ou etapa de compilação. As bibliotecas JavaScript ficam versionadas diretamente na pasta `js/`.

## Pré-requisitos

Para visualizar a página, basta ter um navegador moderno. Para uma experiência de desenvolvimento mais prática, recomenda-se usar o [Visual Studio Code](https://code.visualstudio.com/) com uma extensão de servidor local, como o Live Server.

## Como executar localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/lfbond/projetoFinal_cursoFrontEnd2_DankiCode.git
   ```

2. Entre na pasta do projeto:

   ```bash
   cd projetoFinal_cursoFrontEnd2_DankiCode
   ```

3. Abra o arquivo `index.html` diretamente no navegador ou inicie um servidor local.

   Com o Live Server, clique com o botão direito em `index.html` e selecione **Open with Live Server**. A página será aberta em um endereço local semelhante a `http://127.0.0.1:5500`.

Não é necessário executar `npm install` ou `npm start`.

## Estrutura do projeto

```text
.
├── index.html                 # Página principal e conteúdo das seções
├── css/
│   └── style.css              # Estilos e regras responsivas
├── img/                       # Logos, ícones, fundos e imagens da página
└── js/
    ├── jquery.js              # Biblioteca jQuery incluída localmente
    ├── menu-responsivo.js     # Comportamento do menu mobile
    ├── slick.min.js            # Biblioteca do carrossel
    └── slider.js               # Configuração dos depoimentos
```

## Personalização

- Edite o conteúdo, os textos e as âncoras diretamente no `index.html`.
- Altere cores, espaçamentos e breakpoints em `css/style.css`.
- Substitua os arquivos da pasta `img/` para atualizar a identidade visual.
- Ajuste quantidade de slides, autoplay e comportamento mobile em `js/slider.js`.
- Se o formulário precisar enviar dados de verdade, configure um endpoint no atributo `action` e implemente o tratamento no servidor ou em um serviço de formulários.

## Publicação

Como o projeto é uma página estática, ele pode ser hospedado em serviços como GitHub Pages, Netlify ou Vercel. Para o GitHub Pages, publique a branch que contém o `index.html` na raiz do repositório e selecione a pasta correspondente nas configurações de Pages.

## Contribuição

1. Crie uma branch para sua alteração:

   ```bash
   git checkout -b minha-melhoria
   ```

2. Faça a alteração e teste a página em diferentes tamanhos de tela.
3. Abra um pull request descrevendo o que foi alterado e como validar.

## Licença

Este projeto foi criado para fins educacionais no curso da Danki Code. Não há um arquivo de licença formal no repositório; confirme os termos com o mantenedor antes de reutilizar os materiais ou publicar uma versão derivada.
