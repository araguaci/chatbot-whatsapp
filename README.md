# WhatsApp chatbot using Node.js

Example application using [JavaScript](https://developer.mozilla.org/docs/Web/JavaScript) and [Node.js](https://nodejs.org/) where a simple chatbot will be implemented using the [Zenvia](https://www.zenvia.com/) platform to integrate with WhatsApp and the [AudD](https://audd.io/) platform to integrate with music recognize in order to test some WhatsApp Business API features such as sending and receiving text and file (image and audio) messages.

This tutorial was posted on my [blog](https://rodrigo.kamada.com.br/blog/como-construir-um-chatbot-de-reconhecimento-de-musica-no-canal-whatsapp-usando-nodejs) in portuguese and on the [DEV Community](https://dev.to/rodrigokamada/how-to-build-a-music-recognition-chatbot-on-whatsapp-channel-using-nodejs-bpa) in english.



[![Website](https://shields.braskam.com/v1/shields?name=website&format=rectangle&size=small)](https://rodrigo.kamada.com.br)
[![LinkedIn](https://shields.braskam.com/v1/shields?name=linkedin&format=rectangle&size=small)](https://www.linkedin.com/in/rodrigokamada)
[![Twitter](https://shields.braskam.com/v1/shields?name=twitter&format=rectangle&size=small&socialAccount=rodrigokamada)](https://twitter.com/rodrigokamada)
[![Instagram](https://shields.braskam.com/v1/shields?name=instagram&format=rectangle&size=small&radius=5)](https://www.instagram.com/rodrigokamada)



## Prerequisites


Before you start, you need to install and configure the tools and services:

* [git](https://git-scm.com/)
* [Node.js and npm](https://nodejs.org/)
* IDE (e.g. [Visual Studio Code](https://code.visualstudio.com/))
* [Zenvia](https://app.zenvia.com/) account
* [AudD](https://audd.io/) account
* [ngrok](https://dashboard.ngrok.com/signup) account
* [ngrok documentation](https://ngrok.com/docs#config) documentation

## Tutorial

Já escutou uma música e queria muito saber qual o nome dela? Neste artigo, iremos criar um WhatsApp Bot Node.js que descobre exatamente isso para o usuário. Venha descobrir como! 

* [WhatsApp Bot Node.js](https://www.zenvia.com/blog/developers/whatsapp-bot-nodejs/)

## Getting started


**1.** Clone the repository.

```shell
git clone git@github.com:rodrigokamada/chatbot-whatsapp.git
```

**2.** Install the dependencies.

```shell
npm ci
```

**3.** Change the `.env` file and add the [Zenvia](https://app.zenvia.com/home/api) and [AudD](https://dashboard.audd.io/) tokens. 

**4.** Run the application.

```shell
npm start
```
