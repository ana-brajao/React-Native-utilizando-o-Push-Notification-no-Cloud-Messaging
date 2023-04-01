## Neste PROJETO usaremos SpaceApp, um aplicativo dedicado à postagem de eventos do universo. 

Nós estamos o utilizando desde o curso sobre Firebase Cloud Storage.

Vamos aprender a usar o Push Notification, utilizando Firebase Cloud Messaging — mais um serviço oferecido pelo Firebase. Além da aplicação mobile que vamos desenvolver, também utilizaremos uma aplicação web para simular o envio de notificação. Ela se comunicará com uma API que construiremos ao longo do curso, para enviar notificações de forma personalizada às pessoas usuárias.

Utilizar notificações em um aplicativo é muito relevante, porque alerta a pessoa usuária sobre eventos novos até mesmo se o aplicativo não estiver aberto. Entre outras opções, é possível notificar atualizações, mensagens recebidas ou conteúdos novos que chegaram na aplicação.

Tudo isso é bom para manter o engajamento do uso da nossa aplicação. Às vezes, dependendo da frequência em que o conteúdo é atualizado, a pessoa usuária pode deixar usar a aplicação. As notificações são importíssimas para manter o uso frequente do aplicativo.

Quais os pré-requisitos? Conhecimento do React Native com Expo e Firebase Firestore.

<h4 align="center"> 
	SpaceApp
</h4>

<p align="center">
  <a href="#information_source-o-que-é-o-spaceapp">O que é o SpaceApp?</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## :information_source: O que é o SpaceApp?

O SpaceApp é uma aplicação feita em React Native que permite aos usuários entusiastas sobre astronomia salvarem fotos e informações sobre o espaço. Nessa aplicação foi integrado o Firebase Cloud Messaging para que os usuários possam receber notificações sobre novos conteúdos relacionados ao espaço.

Esse projeto é utilizado no curso de Firebase Cloud Messaging da plataforma da Alura.

<h1 align="center">
    <img alt="Demonstracao" title="Demonstracao" src=".images/demo.gif" width="100%" />
</h1>

## :rocket: Tecnologias

Esse projeto foi desenvolvido com a utilização das seguintes tecnologias:
- [React Native][rn]
- [Expo][expo]


## :information_source: Como usar

Para copiar e executar essa aplicação, você precisa de três pré-requisitos: Git, [Node.js][nodejs] + [Yarn][yarn] intalados no seu computador.

No terminal, digite os comandos a seguir:

### Baixar e instalar o projeto

```bash
# Clonar esse repositório
$ git clone https://github.com/alura-cursos/react-native-firebase-notification.git

# Vá para o ropositório
$ cd react-native-firebase-notification

# Instale as dependências
$ npm install
```

### Executar o Mobile

```bash
# Execute em outro terminal (dentro da pasta SpaceApp)
$ npx expo start
```

Espero que você utilize ao máximo deste projeto para se aprimorar! E se quiser dar um salve, estou lá no LinkedIn 
:wave: 

[nodejs]: https://nodejs.org/
[expo]: https://docs.expo.dev/
[rn]: https://facebook.github.io/react-native/
[yarn]: https://yarnpkg.com/
