<h1 align="center">Authentication API</h1>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-endpoints">Endpoints</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

## 🚀 Tecnologias

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

## 💻 Projeto
API desenvolvida para fornecer Autenticação e Autorização de usuários em uma aplicação Java Spring utilizando o Spring Security. O projeto utiliza PostgreSQL como banco de dados, Spring Security e JWT para controle de autenticação. Projeto assistido e desenvolvido através de [Youtube Tutorial](https://www.youtube.com/watch?v=5w-YCcOjPD0) por [Fernanda Kipper](https://github.com/Fernanda-Kipper). 



## 🏃 Iniciando o Projeto

```bash
git clone https://github.com/denisonkolling/auth-app.git

2. Instale as dependências com o Maven.

3. Instale o [PostgresSQL](https://www.postgresql.org/).
```

## 🔖 Endpoints

```bash
GET /product - Recupere uma lista de todos os produtos. Requer usuário autenticado.

POST /product - Registre um novo produto. Requer acesso de ADMIN.

POST /auth/login - Realize o login na aplicação.

POST /auth/register - Registre um novo usuário na aplicação.
```

##  🔐Usuários

```
USER -> Usuário padrão para usuários logados com permisão de consulta.

ADMIN -> Usuário administrador com permissão de inclusão de novos registros.
```
## 📝 Licença

Esse projeto está sob a licença MIT.

---
