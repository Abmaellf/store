
<h1 align="center"> Loja online </h1>

## Descrição do Projeto
<p align="jutify">Esse projeto consiste em uma aplicação  de loja online.</p>




Conteúdo
=================

<!--ts-->
* [Pre requisitos](#pre-requisitos)
* [Instalação](#instalação)
* [Funcionalidade](#funcionalidades-do-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Bundles e Bibliotecas](#bundles-e-bibliotecas)
* [Inicialização](#inicialização)
* [Executando](#executando-)
* [Colaboradores](#colaboradores)
* [Status](#status)




Pre requisitos
============

* <a href="https://www.docker.com/">Docker</a>
* <a href="https://docs.docker.com/compose/">Docker Compose</a>
* <a href="https://git-scm.com/">Git</a>

Instalação
============



* Efetuar  o clone do repositorio

* Executar o build:

  ``docker compose build``

* Iniciar aplicação:

  ``docker compose up -d``


* Listar os container:

  ``docker compose ps``
  Copiar o ID do container PHP


* Acessar o container do PHP:

  ``docker exec -it {ID do container } bash``

* Executar as migrations:

  ``bin/console doctrine:migration:migrate``


![img_5.png](img_5.png)

Funcionalidades do projeto
============
### Features

- [x] Loja online


Tecnologias utilizadas
============
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
[![PHP Version Require](http://poser.pugx.org/phpunit/phpunit/require/php)](https://packagist.org/packages/phpunit/phpunit)
![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=for-the-badge&logo=symfony&logoColor=white)
![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=black&color=black&labelColor=darkorchid)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

Bundles e Bibliotecas
============
* Doctrine
* Twig
* http-client

Inicialização
============


* Iniciar aplicação:

  ``docker compose up -d``

* Listar os container:

  ``docker compose ps``
    * Copiar o ID do container PHP

* Acessar o container do PHP:

  ``docker exec -it {ID do container } bash``

Colaboradores
============

* <a href="https://github.com/AbmaelFerreira"> Abmael Ferreira</a>



Status
============

<h4 align="left"> 
	  Desafio  🚀 Entregue...  
</h4>