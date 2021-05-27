<h1 align="center">
  <br>
  <br>
  DevPost
</h1>

<h4 align="center">
   App desenvolvido com React Native + NodeJS + Android Studio + FireBase 
</h4>

<h6 align="center">
  bootcamp SujeitoProgramador
</h6>

<br/>

<p align="center">
  <a href="#Pre-Requisitos">Pre-requisitos</a> |
  <a href="#Instalação">Instalação</a> |
  <a href="#Usabilidade">Usabildiade</a>
</p>

# Pre-Requisitos

* [React-Native](https://reactnative.dev/)
* [Android Studio](https://developer.android.com/studio) 
* [Node.JS](https://nodejs.org/)
* [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/get-npm)
* [Firebase](https://firebase.google.com/?hl=pt-br)

# Instalação
```
# Primeiro clone o repositorio do Git para seu computador. Execute o comando; 
git clone https://github.com/SandroFrazaoS/AppDevPost.git

# Acesse a pasta criado atraves do comando; 
cd AppDevPost

# Instale todas as dependencias do projeto, acesse a pasta AppDevPost e execute o comando;
yarn

# Para start do App execute dentro da pasta AppDevPost o comando;
npx react-native run-android
```

# Usabilidade

O App registra posts por usuario, permitir dar like nos posts, cadastrar um novo usuario, incluir e alterar o avatar, filto de busca por usuario e armazenamento dos dados de login.
Foi utilizado como armazenamento dos dados o firebase database e storage. Como controle de acesso foi utilizado o firebase authentication. 

Tela de Login.

![1][tela1]

Tela para criar uma nova conta.

![5][tela6]

Tela Principal onde é mostrados os posts por usuario. Nesta tela é possivel dar likes.

![2][tela3]
 
Cadastrando um novo post

![3][tela4]

Atulização dos dados do usuario, neste tela é posvivel incuir o avatar e alterar o nome do usuario.

![4][tela2]

Filtro de busca por usuario

![5][tela5]

Projeto em Figman
![7][tela7]


[tela1]: Tela1.png
[tela2]: Tela2.png
[tela3]: Tela3.png
[tela4]: Tela4.png
[tela5]: Tela5.png
[tela6]: Tela6.png
[tela7]:Projetodevpost.png