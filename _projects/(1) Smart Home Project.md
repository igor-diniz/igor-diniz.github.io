---
name: Smart Home Data Base Project
tools: [SQL, SQLite]
image: ../imgs/sqlprojectcover.png
description: This is a project in the database context proposed by the Faculty of Engineering of the University of Porto. A database was created, populated and queried according to the real world.
---

# Project Overview

This is a project in the database context proposed by the Faculty of Engineering of the University of Porto. A database was created, populated and queried according to the real world.

The project was designed from the UML to the creation of the database itself. The stages of the project were:
- UML
- Relational schema
- Functional Dependency Analysis
- Decomposition into 3rd Normal Form or Boyce-codd Normal Form
- Implementation of restrictions
- Creation and population of tables in SQLite
- 10 relevant queries and 3 relevant triggers

# Project Report
 If you want to see the complete project report click on the following button.

<p>
{% include elements/button.html link="../imgs/relatorioDoProjeto.pdf" text="See the Report" %}
</p>

## UML
<p>
    <img src="../imgs/casa-inteligenteUML.png" alt="Image" height="100%" width="100%">
</p>

## Database Creation

<p>
{% include elements/button.html link="https://github.com/up202000162/CasaInteligente/blob/main/criar.sql" text="Creation Code" %}
</p>

## Database Population

<p>
{% include elements/button.html link="https://github.com/up202000162/CasaInteligente/blob/main/povoar.sql" text="Population Code" %}
</p>

## Query 1
Quais são os nomes dos modelos de dispositivos que são ou da marca Apple, ou da Microsoft ou da Amazon?

<p>
    <img src="../imgs/answer1.png" alt="Image">
</p>

## Query 2
Qual o idioma mais utilizado nas assistentes virtuais que possuem um número de dispositivos associados acima da média arredondada para 0 casas decimais?

<p>
    <img src="../imgs/answer2.png" alt="Image">
</p>


## Query 3
Quais são os 2 maiores números de utilizadores, por nacionalidade e por idioma das aplicações que controlam? Em caso de empate deve ser selecionado o tuplo cuja nacionalidade seja a menor em ordem alfabética

<p>
    <img src="../imgs/answer3.png" alt="Image">
</p>


## Query 4
Qual o nome, modelo, alcance e velocidade máxima dos dispositivos bluetooth e dos dispositivos wifi da base de dados ordenados por ordem descendente de velocidade máxima?

<p>
    <img src="../imgs/answer4.png" alt="Image">
</p>

## Query 5
Qual o nome do modelo dos comandos infravermelho, cuja aplicação a qual estão associados tenha versão maior que 2.3?

<p>
    <img src="../imgs/answer5.png" alt="Image">
</p>

## Query 6
Qual o nome dos dispositivos que pertencem a um grupo que contenha 'casa' no nome e cuja orientação solar da casa a qual pertencem seja Leste?

<p>
    <img src="../imgs/answer6.png" alt="Image">
</p>

## Query 7
Qual a diferença entre o alcance máximo e mínimo dos dispositivos bluetooth que estão conectados a assistentes virtuais de nome ‘Google Assistant’?

<p>
    <img src="../imgs/answer7.png" alt="Image">
</p>

## Query 8
Quais são as condições que permitem disparar uma ação de ligar ou desligar dispositivos infravermelho por meio de um assistente virtual Alexa?

<p>
    <img src="../imgs/answer8.png" alt="Image">
</p>

## Query 9
Qual é a soma das áreas totais distintas das casas e a quantidade de casas que foram contabilizadas, cujos utilizadores não principais tenham idade superior a 20 anos e controlam aplicações em português?


<p>
    <img src="../imgs/answer9.png" alt="Image">
</p>

## Query 10
Quais são os nomes e modelos e marcas dos dispositivos wifi que não têm uma aplicação associada a eles na base de dados?

<p>
    <img src="../imgs/answer10.png" alt="Image">
</p>

<p class="text-center">
{% include elements/button.html link="https://github.com/up202000162/CasaInteligente" text="Learn More" %}
</p>