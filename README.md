Flask App - Sistema de Login

Este é um simples projeto desenvolvido em Flask, focado na criação de um sistema de login, onde os usuários podem se registrar e autenticar-se. O projeto foi criado para aprimorar meu conhecimento em Python, Flask, SQLAlchemy e segurança de senhas.

Objetivo

O principal objetivo desse repositório é compartilhar o meu aprendizado enquanto estou aprendendo a construir aplicações web com Flask, criando e manipulando usuários de forma segura utilizando técnicas como hashing de senhas. Além disso, quero demonstrar o conhecimento básico sobre CRUD (Create, Read, Update, Delete), que aprendi durante o desenvolvimento desse projeto.

Funcionalidades

Cadastro de Usuário: Os usuários podem se registrar com um nome de usuário, e-mail e senha.
Login de Usuário: Os usuários podem acessar a plataforma inserindo suas credenciais.
Autenticação de Senha: Senhas são armazenadas de maneira segura, utilizando o algoritmo de hashing do werkzeug.
Logout: O sistema oferece a opção de logout para finalizar a sessão.
Tecnologias Utilizadas

Flask: Framework web utilizado para desenvolvimento de aplicações web.
SQLAlchemy: ORM (Object Relational Mapper) para interação com o banco de dados SQLite.
Werkzeug: Biblioteca utilizada para o gerenciamento de senhas, com funções de hashing.
SQLite: Banco de dados utilizado para armazenar informações dos usuários.
Como Executar o Projeto

Requisitos

Python 3.x instalado.
Dependências do projeto, que podem ser instaladas com o comando:

pip install -r requirements.txt

Passos

1. Clone o repositório:

git clone https://github.com/ViniDeiro/flask-app-login.git

2. Acesse a pasta do projeto:

cd flask-app-login

3. Execute a aplicação:

python app.py

4. Acesse http://127.0.0.1:5000/ no seu navegador para ver o sistema em funcionamento.

Melhorias Futuras

Implementar validação de e-mail (ex: enviar um link de verificação de e-mail).
Criar uma página de perfil para os usuários.
Implementar um sistema de recuperação de senha.


Conclusão

Este projeto é apenas o começo da minha jornada no desenvolvimento web, e me ajudou a aprender diversos conceitos importantes, como como criar uma aplicação web simples, trabalhar com autenticação de usuários e proteger as credenciais de forma segura.

Espero poder expandir esse projeto em breve, incluindo novas funcionalidades e melhorando o design da interface.
