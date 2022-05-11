João Vitor Rodrigues Carrijo, RA: 591009
Henrique Rodrigues, RA: 

A aplicação requer o [Node.js](https://nodejs.org/).

```sh
$ npm install
$ npm run start
```

Exemplo de consulta de cep: 

query {
  cep (cep: "17510460") {
    cep
    logradouro
    complemento
    bairro
    localidade
    uf
    ibge
    gia
  }
}
