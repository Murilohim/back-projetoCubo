<h1 align="center">:file_cabinet: Projeto Cubo - back end</h1>

<p align="center">
  <img src="https://cubo.network/assets/images/cubo.svg" width="200">
</p>

## :memo: Descrição
Projeto Full stack realizado como case no curso da Labenu. 
Esse repositório conta com a parte de back end do projeto, no qual foi desenvolvido uma API para o consumo do front, com dois métodos integrados para criação de usuário
e consulta de dados.

## :books: Funcionalidades
* <b>Endpoint de Cadastro</b>: Método que insere no banco de dados, informações como id, nome, sobrenome e participação de um usuário.
* <b>Endpoint de Consulta</b>: Método que consulta a tabela no banco de dados, trazendo todas as informações e registros inseridos.
* <b>Testes</b>: Ampla testagem dos métodos, utilizando Jest.

## 🔗 Link para acessar a documentação

- [Postman](https://documenter.getpostman.com/view/17589027/UVeDtnRS)

## :wrench: Tecnologias utilizadas
As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com)
- [Knex](https://knexjs.org/)
- [Jest](https://jestjs.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Dotenv](https://www.npmjs.com/package/dotenv)

## :rocket: Rodando o projeto

Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
- Antes de começar, você irá precisar instalar o [Git](https://git-scm.com/), [NodeJS](https://nodejs.org/pt-br/download/) + [Visual Studio Code](https://code.visualstudio.com/).

```# Versões mínimas ou superiores.
$ node -v
v12.19.0

$ npm -v
6.14.5
```

- Para configurar, no GitBash digite os seguinte códigos:

```# Clonar o repositório
$ git clone "https://github.com/Murilohim/back-projetoCubo.git"

#Entrar no diretório
$ cd ./back-projetoCubo

#Abrir projeto no VsCode ou com seu prompt de comando de preferência
code . ||  cd ./back-projetoCubo (Passo acima) 

#Com o terminal aberto rodar o comando
$ npm install (para instalar as dependências necessárias)

#Lembre-se de substituir as informações do banco de dados com as informações de seu banco e/ou criar um arquivo .env com essas variáveis sesíveis.
No aqui BaseDatabse.ts, dentro da pasta data.

#Rode o comando migration para a acriação da tabela em seu database
$ npm run migrations

#Agora só rodar o projeto com o comando
$ npm run start ou npm run dev

```

## :soon: Implementação futura
* Criação de dois métodos adicionais: Deletar um usuário e consulta específica por usuário.

## :handshake: Colaboradores
<table>
  <tr>
    <td align="center">
      <a href="http://github.com/murilohim">
        <img src="https://avatars.githubusercontent.com/u/84817937?s=400&u=889026ba86ed2fc84b6a1719fa7fbed7b6289128&v=4" width="100px;" alt="Foto de Murilo Terenciani no GitHub"/><br>
        <sub>
          <b>Murilohim</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## :dart: Status do projeto
🟢 Finalizado
