# 💰 PayPal Payment

## ⚒️ Ferramentas utilizadas 
  
  - Node.js
  - Express
  - PayPal API REST

## 👨‍💻 Executando localmente 

Assegure-se de ter [Node.js](http://nodejs.org/) instalado

- 1º Clone o projeto:

```shell script
$ git https://github.com/brduarte/paypal-payment.git # ou clone seu próprio fork
```

- 2º Você precisa ativar API do [Distance Matrix API](https://developers.google.com/maps/documentation/distance-matrix/start) do Google Maps
- 3º Na pasta raiz é preciso renomear o arquivo 'config.exemplo.js' para 'config.js'

Ex: /config.js
```js script
    googleAPi: {
        maps: {
            url: "https://maps.googleapis.com/maps",
            distanceMatrix: {
                uri: 'api/distancematrix/json',
                language: "pt-BR",
                units: "matric",
                key: ""
            }
        }
    }
```

- 4º depois é só executar o projeto

```shell script
$ npm install
$ npm start
```

Seu aplicativo agora deve estar sendo executado em [localhost:3000](http://localhost:3000/).

Você pode fazer um teste rápido em: [https://paypal-payment.herokuapp.com/](https://paypal-payment.herokuapp.com/)

## 📝 Documentações 

Para obter mais informações das ferramentas utilizadas:

- [Node.js](https://nodejs.org/en/docs/)
- [Express](https://expressjs.com/pt-br/)
- [PayPal API REST](https://developer.paypal.com/docs/api/overview/)

## Autor

| [<img width="125px" src="https://avatars2.githubusercontent.com/u/29002558?v=4"><br><sub>@brduarte</sub>](https://github.com/brduarte)|
| :---: |
