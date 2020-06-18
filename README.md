# Image-Uploader
Image uploader desenvolvido apenas Back-end desenvolvido em NodeJS.

## Execução
Tenha o NodeJs instalado em sua máquina;
tenha o yarn instalado em sua máquinha;

Clone o repositório e na pasta /backend rode o comando:

```javascript
$ npm install
```
Para iniciar o back-end rode o comando:

```javascript
$ yarn dev
```
ou

```javascript
$ npm start
```

Para testar você pode enviar uma requisição do tipo post para: `http://localhost:3000/posts`
Contendo um nome e um arquivo de imagem.

A imagem será salva em: `./backend/src/tmp/uploads`
