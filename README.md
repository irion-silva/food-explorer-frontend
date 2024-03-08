# Food Explorer

## Sumário
- [Demonstração da aplicação](#demonstração-da-aplicação)
- [Descrição do projeto](#descrição-do-projeto)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Acesso ao projeto](#acesso-ao-projeto)
- [Como utilizar](#como-utilizar)

- [Créditos](#créditos)
- [Pessoa desenvolvedora do projeto](#pessoa-desenvolvedora-do-projeto)

## Demonstração da aplicação
<div align="center">
  <img src="https://i.imgur.com/1YM3QkL.png" alt="Aplicação Food explorer" width="600" height="300"/>
</div>

## Descrição do projeto
O Food Explorer é um site de restaurante que permite aos usuários se registrarem, fazerem pedidos e acompanharem seu status. Eles podem personalizar seus perfis, marcar itens como favoritos, procurar por pratos e entrar em contato com o restaurante. O carrinho de compras funciona perfeitamente e oferece duas opções de pagamento: cartão ou Pix. Os administradores têm controle total sobre os pratos, podendo adicioná-los, editá-los ou removê-los conforme desejarem. Eles também podem atualizar o status dos pedidos de acordo com a preparação na cozinha, e essas alterações são refletidas instantaneamente para os clientes. O projeto apresenta várias funcionalidades adicionais, como a capacidade de alterar o tema da página, personalizar o perfil do usuário e efeitos visuais atrativos. Além disso, é responsivo, adaptando-se a diferentes dispositivos. O repositório contém os dados tanto do Frontend em React.js quanto do Backend em Node.js.

## Tecnologias utilizadas
- Axios
- BCryptjs
- CORS
- Express
- Javascript
- JSON Web Token
- Knex
- Multer
- Node.js
- Nodemon
- React Icons
- React Router Dom
- ReactJs
- SQLite
- Styled Components
- Vite

## Acesso ao projeto
O projeto está disponível no seguinte link: [link para o website](https://food-explorer-site.netlify.app/).

## Como utilizar
Clone o projeto para o local desejado em seu computador.

```bash
$ git clone git@github.com:irion-silva/food-explorer-frontend.git
```
___

#### Executando o BackEnd
```bash
# No BackEnd insira uma porta e um secret no arquivo .env vazio
  AUTH_SECRET=
  PORT=

# Navegue até o diretório do BackEnd
$ cd food-explorer-backend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do BackEnd
$ npm run dev
```
___

#### Executando o FrontEnd
```bash
# Navegue até o diretório do FrontEnd
$ cd food-explorer-frontend

# Instale as dependências necessárias
$ npm install

# Agora inicie o servidor do FrontEnd
$ npm run dev

# O terminal irá exibir o endereço local onde a aplicação está sendo executada. Basta digitar o mesmo endereço em seu navegador preferido. O endereço usado na criação do projeto foi este:

  http://localhost:5173/
```

#### Deseja visualizar como a aplicação é apresentada para o administrador? Utilize as credenciais abaixo:
```bash
  e-mail: admin@foodexplorer.com
  senha: 123456
```
___

O BackEnd foi diretamente hospedado no Render, enquanto o FrontEnd foi diretamente hospedado no Netlify.

## Créditos
- Rocketseat

## Pessoa desenvolvedora do projeto
A seguinte pessoa desenvolveu este projeto:

[<img src="https://avatars.githubusercontent.com/u/83726646?v=4" width=115><br><sub>Irion Francisco da Silva</sub>](https://github.com/irion-silva)
