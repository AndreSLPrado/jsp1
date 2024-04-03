CREATE TABLE cliente (
    id INT NOT NULL AUTO_INCREMENT,
    nome VARCHAR(45) NULL,
    sobrenome VARCHAR(45) NULL,
    login VARCHAR(45) NULL,
    senha VARCHAR(45) NULL,
    endereco VARCHAR(45) NULL,
    contato VARCHAR(45) NULL,
    PRIMARY KEY (id)
);

INSERT INTO Cliente(nome,sobrenome,login,senha,endereco,contato)
VALUES ('ANDRE','SILVA','andre',md5('teste'),'guara','61993704082');
