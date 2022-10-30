<p align="center">
  <img src="./web/src/assets/logo.svg" alt="Logo" width="300"/>
  <br>
</p>

<br>

<p align="center">
  <img src="https://img.shields.io/static/v1?label=DO&message=WHILE&color=blueviolet&style=for-the-badge"/>
  <img src="https://img.shields.io/github/license/MrRioja/nlw-heat?color=blueviolet&logo=License&style=for-the-badge"/>
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/MrRioja/nlw-heat?color=blueviolet&logo=elixir&logoColor=white&style=for-the-badge">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/MrRioja/nlw-heat?color=blueviolet&style=for-the-badge">
</p>
<br>

<p align="center">
  <a href="#sobre">Sobre</a> •
  <a href="#nlw-heat">NLW Heat</a> •
  <a href="#instalação">Instalação</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#autor">Autor</a>  
</p>

<br><br><br>

## Sobre

Projeto desenvolvido durante a NLW Heat, evento criado pela RocketSeat. Um evento 100% online e GRATUITO, com conteúdo exclusivo e INÉDITO.

Ocorreu do dia 18 ao dia 24 de Outubro de 2021 e teve como intuito mostrar na prática o poder da stack NodeJS + ReactJS + React Native e como essas tecnologias podem te levar até os seus maiores objetivos como programador.

<img src="./readme/wallpaper.png" alt="NLW Heat Wallpaper" />

## NLW Heat

O NLW Heat foi uma aplicação voltada para o DoWhile 2021 cujo objetivo principal era reproduzir, tanto na web quanto no mobile, os comentários realizados sobre o evento em tempo real.
O login dos espectadores é feito com a conta do Github e abaixo podemos ver a home da aplicação com o botão para realizar o login para que o usuário possa comentar sobre o evento:

![Home web](./readme/home-web.png)

Após o login feito utilizando a conta do Github, uma caixa de texto é exibida para que o usuário possa registrar seu comentário e torna-lo publico, conforme podemos ver a seguir:

![Home web com login realizado](./readme/home-logged-web.png)

Feito isso o usuário já estará apto a realizar seus comentários que serão exibidos conforme imagem abaixo:

![Home web com comentários](./readme/home-with-message-web.png)

No mobile o comportamento é o mesmo. Inicialmente o usuário terá a opção de login com o Github e o mural com os comentários já enviados por outros usuários:

<img src="./readme/home-mobile.png" alt="Home mobile sem comentários enviados" width="250" />

Após comentários serem enviados por outros usuários, eles já serão disponibilizados nos murais independentemente do login ser realizado ou não, pois o login é necessários apenas para comentar e não para visualizar os comentários, conforme ilustrado a seguir:

<img src="./readme/home-with-message-mobile.png" alt="Home mobile com comentários enviados" width="250" />

Por fim, deixo o GIF abaixo para ilustrar o funcionamento da aplicação de maneira geral:

![Demonstração da aplicação web](./readme/demo-app-web.gif)

## Instalação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/nlw-heat.git

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-heat

# Vá para a pasta server
$ cd backend

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn dev

# O servidor inciará na porta 4000 - acesse <http://localhost:4000>
```

### 🖥️ Rodando o Front End (Web)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/nlw-heat.git

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-heat

# Vá para a pasta server
$ cd web

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn dev

# O servidor inciará na porta 3000 - acesse <http://localhost:3000>
```

### 📱 Rodando o App (Mobile)

```bash
# Clone este repositório
$ git clone git@github.com:MrRioja/nlw-heat.git

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw-heat

# Vá para a pasta server
$ cd mobile

# Instale as dependências
$ npm install
# Caso prefira usar o Yarn execute o comando abaixo
$ yarn

# Execute a aplicação
$ expo start

# Será aberto no terminal o menu do Expo onde poderá scanear o QR Code para executar o app diretamente no seu celular ou as opções de executar no emulador android ou iOS
```

## Tecnologias

<img align="left" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="75" />

<img align="left" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="75"/>

<img align="left" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="75" />

<img align="left" src="https://www.svgrepo.com/show/353722/expo.svg" alt="Expo" height="100" />

<br><br><br><br><br><br>

## Autor

<div align="center">
<img src="https://images.weserv.nl/?url=avatars.githubusercontent.com/u/55336456?v=4&h=100&w=100&fit=cover&mask=circle&maxage=7d" />
<h1>Luiz Rioja</h1>
<strong>Backend Developer</strong>
<br/>
<br/>

<a href="https://linkedin.com/in/luizrioja" target="_blank">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://github.com/mrrioja" target="_blank">
<img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="mailto:lulyrioja@gmail.com?subject=Fala%20Dev" target="_blank">
<img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://api.whatsapp.com/send?phone=5511933572652" target="_blank">
<img alt="WhatsApp" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
</a>

<a href="https://join.skype.com/invite/tvBbOq03j5Uu" target="_blank">
<img alt="Skype" src="https://img.shields.io/badge/SKYPE-%2300AFF0.svg?style=for-the-badge&logo=Skype&logoColor=white"/>
</a>

<br/>
<br/>
</div>
