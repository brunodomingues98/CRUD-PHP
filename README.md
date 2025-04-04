📄 CRUD Simples em PHP com MySQL

Este projeto é uma implementação simples de um sistema CRUD (Create, Read, Update, Delete) utilizando PHP e MySQL, com uma única página (index.php) e um script SQL para criação da tabela no banco de dados.

✅ Funcionalidades

Inserir novos registros

Listar registros existentes

Editar registros

Deletar registros

Tudo feito na mesma página (index.php), com base em parâmetros GET e POST.

🚀 Tecnologias utilizadas

PHP (sem frameworks)

MySQL

HTML + CSS inline

⚙️ Como rodar o projeto localmente

1. Clonar o repositório

git clone https://github.com/brunodomingues98/CRUD-PHP.git
cd CRUD-PHP

2. Criar o banco de dados

Acesse seu gerenciador MySQL (ex: phpMyAdmin)

Execute o script contido no arquivo database.sql:

CREATE TABLE IF NOT EXISTS users (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100) NOT NULL,
  email VARCHAR(100) NOT NULL
);

3. Configurar o banco de dados no código (se necessário)

Abra o arquivo index.php e edite as credenciais de acesso:

$host = "localhost";
$user = "root";
$password = "";
$database = "crud"; // ou o nome que você criou

4. Rodar o projeto

Coloque o projeto na pasta htdocs (se estiver usando XAMPP ou WAMP) e acesse:

http://localhost/CRUD-PHP/index.php

📁 Estrutura do projeto

CRUD-PHP/
├── index.php        # Interface e lógica principal do CRUD
└── database.sql     # Script para criação da tabela no MySQL

📌 Melhorias futuras

Separar o código em múltiplos arquivos (MVC)

Estilização com CSS externo ou frameworks (ex: Bootstrap)

Validação de formulário no frontend

Prevenção contra SQL Injection (uso de prepared statements)

Sistema de login/autenticação

📜 Licença

Este projeto é livre para estudos e modificação. Sinta-se à vontade para usar e melhorar!

Feito com ❤️ por Bruno Domingues

