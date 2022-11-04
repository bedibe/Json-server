<h1 align="center"> 

![Logo](https://miro.medium.com/max/720/0*vL991M8tdcYYOsms) </h1>

<p align="center">
 <a href="#sobre">Sobre</a> •
 <a href="#pré-requisitos">Pré-Requisitos</a> • 
 <a href="#rodando-o-back-end-servidor">Rodando Backend</a> • 
 <a href="#tecnologias">Tecnologias</a> • 
<a href="#testes-unitários">Testes</a> • 
<a href="#autoria">Autoria</a>
</p>

<h1 align="center"> - API Rest</h1>

### Sobre

Criação de API que retorna informações sobre os `materiais` de um estúdio de tatuagem, utilizando os verbos HTTP seguindo o padrão REST e contendo todas as operações de CRUD.

---
### Pré-requisitos 

Antes de começar, você precisa ter instalado em sua máquina as seguintes ferramentas:

[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/).

---
### Rodando o Back End (servidor) 

```bash
# Clone este repositório
$ git clone <https://github.com/bedibe/Json-server>

# Acesse a pasta do projeto no terminal/cmd
$ cd Projetoim3-json_server / Json-server

# Vá para a pasta server
$ cd server

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3000 - acesse <http://localhost:3000>
```

---
### Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

*Ferramentas*

Node.js prompt de comando
</br>
VS Code
</br>
Render
</br>
Postman
</br>
---
### Demonstração da aplicação

O protocolo HTTP implementa diferentes verbos. A ideia por trás de uma API ou aplicação Rest é que *cada um dos diferentes verbos seja utilizado para uma operação específica.*

cada operação CRUD utilizará um verbo http diferente:

O verbo `post` é utilizado para inserir recursos/registros no banco. A operação CRUD equivalente é a de `create`.

O verbo `get` é utilizado para retornar os recursos. A operação CRUD equivalente é a de `read`.

O verbo `put` é utilizado para atualizar recursos/registros específicos no banco. A operação CRUD equivalente é a de `update`.

O verbo `delete` é utilizado para receber um parâmetro para deleção. A operação CRUD equivalente é a de `delete`.

---

### Testes Unitários

O arquivo de testes foi implementado ao projeto para conferir o funcionamento das rotas através da biblioteca [Render](https://render.com/).

 Você pode optar pela mesma ou instalar outra ferramenta semelhante como o [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/).

---

### Autoria

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/bernardo-adelino-1a9335232/)]() 
[![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat-square&logo=Gmail&logoColor=white&link=mailto:cardosovanessafs@gmail.com)](mailto:beadelino@gmail.com) 


<p>Feito por Bernardo Rezende!</p>

