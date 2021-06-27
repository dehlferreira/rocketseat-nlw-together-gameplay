<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-branchs">Branchs</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-pré-requisitos">Pré-Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-configuração">Configuração</a>&nbsp;&nbsp;&nbsp;
  <br>
  <a href="#-instalando-dependências">Instalando dependências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-iniciando-aplicação">Iniciando aplicação</a>&nbsp;&nbsp;&nbsp;

</p>

## Repositório criado para meu estudo da NLW - Together realizado pela

<h2 align="center">🚀 Rocketseat</h2>

<br>

<h1 align="center">
  <img alt="GamePlay" height="80" title="Plant Manager" src="assets/logo.png" />
</h1>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=E51C44&labelColor=0A1033">

 <img src="https://img.shields.io/static/v1?label=NLW&message=06&color=E51C44&labelColor=0A1033" alt="NLW 06" />
</p>

![cover](assets/cover.png?style=flat)

## 💻 Projeto

Aplicativo para lhe ajudar a conectar-se e organiza o momento de diversão e jogar com os amigos. Crie grupos para jogar seus games favoritos com seus amigos com esse App que possui autenticação com Discord.

## ⏱ Branchs

Caso queira acompanhar como foi a evolução durante a semana, segue abaixo os links para as branchs criadas conforme as aulas foram sendo liberadas durante a NLW:

- [1º Dia - feat/first-day](https://github.com/dehlferreira/rocketseat-nlw-together-gameplay/tree/feat/first-day)
- [2º Dia - feat/second-day](https://github.com/dehlferreira/rocketseat-nlw-together-gameplay/tree/feat/second-day)
- [3º Dia - feat/third-day](https://github.com/dehlferreira/rocketseat-nlw-together-gameplay/tree/feat/third-day)
- [4º Dia - feat/fourth-day](https://github.com/dehlferreira/rocketseat-nlw-together-gameplay/tree/feat/fourth-day)
- [5º Dia - feat/fifth-day](https://github.com/dehlferreira/rocketseat-nlw-together-gameplay/tree/feat/fifth-day)

## 🛠 Features

- Autenticação Social OAuth2 com servidor do Discord
- Obtém perfil do usuário cadastro no Discord (username e avatar)
- Lista os servidores do Discord que o usuário faz parte
- Permite realizar o agendamento de partidas
- Permite filtrar as partidas por categoria
- Exibe se a partida foi agendada em um servidor próprio (anfitrião) ou em servidores de outros (convidado)
- Compartilha o convite para ingressar no servidor do usuário
- Permite redirecionar o usuário para o seu próprio servidor
- Disponibiliza a função de Logout

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React Native](https://reactnative.dev/docs/getting-started)
- [Typescript](https://www.typescriptlang.org/docs/)
- [Expo](https://docs.expo.io/)
- [Context API](https://pt-br.reactjs.org/docs/context.html)
- [Async Storage](https://reactnative.dev/docs/asyncstorage)
- [Vector Icons](https://docs.expo.io/guides/icons/)
- [React Native Svg e Svg Transform](https://docs.expo.io/versions/latest/sdk/svg/)
- [Axios](https://www.npmjs.com/package/axios)
- [Gradient colors](https://docs.expo.io/versions/latest/sdk/linear-gradient/)
- [OAuth2 Discord ](https://discord.com/developers/docs/topics/oauth2)
- [Expo Google Fonts](https://docs.expo.io/guides/using-custom-fonts/)
- [React Navigation Stack](https://reactnavigation.org/docs/stack-navigator/)
- [React Native Gesture Handler](https://reactnavigation.org/docs/getting-started)
- [Expo Authentication](https://docs.expo.io/guides/authentication/)
- [React Native Share](https://reactnative.dev/docs/share)
- [Deep Link](https://reactnavigation.org/docs/deep-linking/)

## 🔖 Layout

Nos links abaixo você encontra o layout do projeto web. Lembrando que você precisa ter uma conta no [Figma](http://figma.com/) para acessá-lo.

- [Layout](https://www.figma.com/file/0kv33XYjvOgvKGKHBaiR07/GamePlay-NLW-Together?node-id=58913%3A83)

## ⚙ Pré-Requisitos

- [Node](https://nodejs.org/pt-br/)
- [Yarn](https://yarnpkg.com/getting-started)
- [Expo](https://docs.expo.io/)

## ⚙ Configuração

No terminal clone o projeto para o diretório desejado:

```
git clone https://github.com/dehlferreira/rocketseat-nlw-together-gameplay.git
```

## ⚙ Instalando dependências

Para instalar, acesse o diretório onde você clonou o projeto:

```
cd rocketseat-nlw-together-gameplay
```

Instale as dependências:

```
yarn install
```

## ▶ Iniciando aplicação

Ainda no diretório do projeto, execute o comando no terminal:

```
expo start
```

Lembre-se de criar o seu App no servidor do Discord para obter as credencias de autenticação. Em seguida, defina no arquivo .env as configurações do seu App (remova o example do arquivo .env.example).

```cl
REDIRECT_URI=
SCOPE=
RESPONSE_TYPE=
CLIENT_ID=
CDN_IMAGE=
```

---

Feito com ♥ by Rocketseat :wave: [Participe da nossa comunidade!](https://discordapp.com/invite/gCRAFhc)

 <!-- coisas para acrescentar conforme evolução -->
<!-- - [Layout Mobile](https://www.figma.com/file/X27FfVxAgy9f5IFa7ONlph/Happy-Mobile) -->
