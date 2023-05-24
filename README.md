<p align="center">
        <img height="150" width="150" src="https://camo.githubusercontent.com/002313a28ac7d09f24e8a70358139bb4f7c2c32eaf83a926e873bedf67b69eac/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f654e41736a4f353574506267616f72376d612f67697068792e676966">
  <h1 align="center">Guia Extenso de ReactJS</h1>
</p>

## :dart: O guia para te ajudar em novos projetos.

> Este guia abrangente fornecerá todas as instruções necessárias para a instalação e configuração do ReactJS em sistemas Windows, Linux e MacOS. Siga os passos abaixo para configurar o ambiente de desenvolvimento em seu sistema operacional preferido.

## :open_book: Sumário

- Instalações:
    - [Nodejs](#nodejs) <br>
        - [NodeJS Windows](#nodejs) <br>
        - [Nodejs MacOS](#nodejs-macos) <br>
        - [Nodejs Linux](#nodejs-linux) <br>
    - [Extensões VsCode](#extensoes) <br>
<!-- - Configuração:
    - [Frontend](#-nodejs) <br>
    - [Backend](#-nodejs) <br>
- Modulos Interessantes:
    - [Gratuitos](#-nodejs) <br>
    - [Pagos](#-nodejs) <br>
- Recomendações:
    - [Canais do Youtube](#-nodejs) <br>
    - [Onde ler artigos](#-nodejs) <br>
    - [Comunidades](#-nodejs) <br>
    - [Podcasts](#-nodejs) <br>
    - [Livros](#-nodejs) <br> -->
- Tirar Dúvidas
    - [Fazer perguntas](https://github.com/cvrocha/react-guide/issues)

---

<div id="nodejs"></div>

## :hammer_and_wrench: Instalações Essenciais:


### NodeJS Windows:
- Acesse o site oficial do **NODEJS** **https://nodejs.org/en/download**
- Execute o instalador, siga as instruções na tela e pronto.
- Agora, o Node.js está instalado em seu computador Windows. Para verificar se a instalação foi bem-sucedida, abra o prompt de comando e execute o seguinte comando:
```
node -v
```
---
<div id="nodejs-macos"></div>

### NodeJS MacOS:
- Acesse o site oficial do **NODEJS** **https://nodejs.org/en/download**
- Execute o instalador, siga as instruções na tela e pronto.
- Agora, o Node.js está instalado em seu computador MacOS. Para verificar se a instalação foi bem-sucedida, abra o terminal e execute o seguinte comando:
```
node -v
```
----- **Usando o Homebrew** -----
- Se você não tiver o Homebrew instalado, execute o seguinte comando no Terminal para instalá-lo:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
- Após a instalação do Homebrew, execute o seguinte comando no Terminal para instalar o Node.js:
```
brew install node
```
- Aguarde até que a instalação seja concluída. O Homebrew instalará tanto o Node.js quanto o npm (gerenciador de pacotes do Node.js) automaticamente.
- Para verificar se a instalação foi bem-sucedida, execute o seguinte comando no Terminal:
```
node -v
```
----- **Usando o NVM (Node Version Manager)** -----
- Se você preferir usar o NVM para gerenciar as versões do Node.js, execute o seguinte comando no Terminal para instalar o NVM:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash
```
- Após a instalação do NVM, feche e abra o Terminal novamente ou execute o seguinte comando para carregar o NVM:
```
source ~/.nvm/nvm.sh
```
- Agora, você pode instalar uma versão específica do Node.js usando o NVM. Por exemplo, para instalar a versão mais recente do Node.js, execute o seguinte comando:
```
nvm install node
```
- Aguarde até que a instalação seja concluída. O NVM instalará tanto o Node.js quanto o npm automaticamente.
- Para verificar se a instalação foi bem-sucedida, execute o seguinte comando no Terminal:
```
node -v
```
---
<div id="nodejs-linux"></div>

### NodeJS Linux (Ubuntu e Debian):
- Acesse o site oficial do **NODEJS** **https://nodejs.org/en/download**
- Execute o instalador, siga as instruções na tela e pronto.
- Agora, o Node.js está instalado em seu computador Windows. Para verificar se a instalação foi bem-sucedida, abra o prompt de comando e execute o seguinte comando:
```
node -v
```
----- **Usando o terminal bash ou zsh** -----
- Execute o primeiro comando
```
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash - &&\
```
- Execute o segundo comando
```
sudo apt-get install -y nodejs
```


---
<div id="extensoes"></div>

## 💡 Extensões:
> As extensões no Visual Studio Code (VSCode) são recursos adicionais que permitem estender a funcionalidade do editor de código. 

### ESLint:
O ESLint é uma ferramenta de análise estática de código JavaScript que ajuda a identificar e corrigir erros e padrões de código inconsistentes. A extensão do ESLint para o VSCode integra-se perfeitamente ao editor, exibindo avisos e erros de linting em tempo real.

<a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint">Saiba Mais 🔗</a>

#

### Prettier:
O Prettier é uma extensão que ajuda a formatar automaticamente o código JavaScript, incluindo código ReactJS, seguindo convenções de estilo pré-definidas. Ele pode ajudar a manter um estilo de código consistente em toda a equipe.

<a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">Saiba Mais 🔗</a>

#

### Bracket Pair Colorizer:
Essa extensão destaca os pares de colchetes, chaves e parênteses com cores diferentes, facilitando a visualização e a correspondência deles em código JSX complexo.

<a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2">Saiba Mais 🔗</a>
#

### EditorConfig:
é usada para fornecer suporte à configuração consistente e compartilhada de estilos de código entre diferentes editores de texto e IDEs.

<a href="https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig">Saiba Mais 🔗</a>

#

### vscode-styled-components:
é projetada especificamente para fornecer suporte aprimorado ao desenvolvimento com a biblioteca Styled Components no Visual Studio Code.
Styled Components é uma biblioteca popular para estilização de componentes em aplicações React. Ela permite escrever estilos CSS diretamente no código JavaScript ou TypeScript, oferecendo uma abordagem de estilização mais intuitiva e fácil de manter.

<a href="https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components">Saiba Mais 🔗</a>

#

### Rocketseat ReactJS:
Snippets: Ela fornece uma coleção de snippets (trechos de código) pré-configurados para facilitar a escrita de código ReactJS. Os snippets são atalhos que podem ser usados para gerar blocos de código comuns, como componentes, importações, hooks e estruturas básicas de código ReactJS.

<a href="https://marketplace.visualstudio.com/items?itemName=rocketseat.RocketseatReactJS">Saiba Mais 🔗</a>

#

### Auto Rename Tag:
tem como objetivo facilitar a edição e a manutenção de código HTML/XML no Visual Studio Code. Essa extensão oferece o recurso de renomeação automática de tags. Quando você renomeia uma tag de abertura ou fechamento de um elemento HTML/XML, a extensão atualiza automaticamente a tag correspondente, mantendo a consistência do código.

<a href="https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag">Saiba Mais 🔗</a>

#

### Color Highlight:
tem como finalidade auxiliar no desenvolvimento de estilos CSS, SCSS, Less e Stylus, fornecendo um destaque visual para cores presentes no código. Quando você utiliza valores de cores em formato hexadecimal (por exemplo, #FF0000 para vermelho) ou em outros formatos (como rgb(255, 0, 0)), a extensão "ColorHighlight" identifica essas cores e destaca visualmente o texto correspondente com a cor definida.

<a href="https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight">Saiba Mais 🔗</a>

#

### Prisma:
é projetada para fornecer suporte ao desenvolvimento de bancos de dados com a biblioteca Prisma no Visual Studio Code. O Prisma é um ORM (Object-Relational Mapping) moderno e avançado que simplifica o acesso e a manipulação de bancos de dados em aplicativos. Ele oferece uma camada de abstração para interagir com o banco de dados, permitindo que você escreva consultas e operações de banco de dados usando uma linguagem de programação amigável, como JavaScript ou TypeScript.

<a href="https://marketplace.visualstudio.com/items?itemName=Prisma.prisma">Saiba Mais 🔗</a>

#

### Tailwind CSS IntelliSense:
é projetada para fornecer suporte ao desenvolvimento com o framework CSS chamado Tailwind CSS no Visual Studio Code. O Tailwind CSS é um framework CSS altamente configurável e de baixo nível, que permite a criação rápida e flexível de interfaces de usuário. Ele fornece uma ampla gama de utilitários de classe CSS que podem ser combinados para criar estilos personalizados.

<a href="https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss">Saiba Mais 🔗</a>

#

### PostCSS Language Support:
fornece suporte aprimorado ao desenvolvimento com a linguagem PostCSS no Visual Studio Code. O PostCSS é uma ferramenta de processamento de CSS que permite estender e transformar as funcionalidades do CSS tradicional através do uso de plugins. Ele permite que você utilize recursos avançados, como variáveis, mixins, aninhamento e até mesmo pré-processadores CSS populares, como o Sass, no seu fluxo de trabalho de desenvolvimento.

<a href="https://marketplace.visualstudio.com/items?itemName=csstools.postcss">Saiba Mais 🔗</a>

#

### Npm Intellisense:
 tem como objetivo fornecer suporte ao desenvolvimento com o gerenciador de pacotes npm no Visual Studio Code. O npm (Node Package Manager) é um gerenciador de pacotes amplamente utilizado no ecossistema do Node.js. Ele permite que você instale, gerencie e utilize pacotes e dependências em seus projetos.

<a href="https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense">Saiba Mais 🔗</a>

#

## Contribuidores ✨

Obrigado a essas pessoas maravilhosas:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/cvrocha"><img src="https://avatars.githubusercontent.com/u/62439381?v=4" width="100px;" alt=""/><br /><sub><b>Caio Rocha</b></sub></a><br /><a href="https://github.com/jjeanjacques10/guia-programador-junior/commits?author=LucasOliveiraS" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

#  

Copyright (c) 2023
