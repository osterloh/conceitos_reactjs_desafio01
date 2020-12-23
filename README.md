<h2 align="center"><a href="https://rocketseat.com.br/" target="_blank" style="text-decoration: none">
    <img alt="Bootacmp GoStack" src="https://camo.githubusercontent.com/0a35fb0a0add717a1556200218530580cca84bfd7a0e8c3f5c28fc72e02cd3fb/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f676f6c64656e2d77696e642f626f6f7463616d702d676f737461636b2f6865616465722d6465736166696f732d6e65772e706e67" width="50%"/>
    <br>
    Desafio 01 do Bootcamp GoStack
    <br>
    Introdução ao ReactJS
</a></h2>

<div>
  <img alt="GIF projeto" src="assets/desafio02.gif">
</div>

## Descrição

- Este projeto foi desenvolvido com a finalidade de cumprir o desafio 01 do Bootacamp GoStack da [Rocketseat](https://rocketseat.com.br/), utilizando o <strong>[ReactJS](https://pt-br.reactjs.org/)</strong> para fins de capacitação pessoal.
- A finalidade desse projeto é conectar o projeto front-end ao back-end e cadastrar os Repositórios com as Tecnologias de um DEV e deltar esses dados.

## Etapas

- Para cumprir o desafio foram utilizadas e configuradas as rotas http GET, POST e DELETE.

```bash
* GET: Buscar informações do back-end;
* POST: Criar uma informação no back-end;
* DELETE: Deletar uma informação no back-end;
```

- Para cadastrar um repositório foi utilizado o método http POST para a rota "/repositories", passando como requisição body os seguintes dados em formato de json:

```js
{
  title, url, techs;
}
```

- Para listar os dados cadastrados foi utilizado o método http GET para a rota "/repositories".

- Para deletar algum dado cadastrato é utilizado o método http DELETE para a rota "/repositories/:id", passando como uma requisição de parâmetro o ID do repositório.

## Tecnologias

- [ReactJS](https://pt-br.reactjs.org/)
- [yarn](https://yarnpkg.com/)
- [axios](https://github.com/axios/axios)

---

Desenvolvido por [Johnatan Luiz Osterloh](https://www.linkedin.com/in/johnatanosterloh/)
