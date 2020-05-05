CREATE DATABASE clinica;
use clinica;

CREATE TABLE clientesnutri(
    id int PRIMARY KEY AUTO_INCREMENT,
    cliente varchar(100) not null,
    valor real not null,
    data date not null,
    horario time not null
    )
    
    
CREATE TABLE clientesof(
    id int PRIMARY KEY AUTO_INCREMENT,
    cliente varchar(100) not null,
    valor real not null,
    data date not null,
    horario time not null
    )
    
    
CREATE TABLE clientespsi(
    id int PRIMARY KEY AUTO_INCREMENT,
    cliente varchar(100) not null,
    valor real not null,
    data date not null,
    horario time not null
    )
