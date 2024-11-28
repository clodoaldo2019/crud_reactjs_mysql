# crud_reactjs_mysql
Exemplo de CRUD com ReactJS e Mysql. 

Banco e tabela criados no mysql - conexão root
**********************************************

CREATE DATABASE IF NOT EXISTS meubanco;

use meubanco;

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    mane VARCHAR(255) NOT NULL,
    email VARCHAR(255) UNIQUE NOT NULL
);
