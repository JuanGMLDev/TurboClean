# TurboClean 
!! --- ATANÇÃO: ESSE PROGRAMA NÃO FOI DESENVOLVIDO PARA USO EMPRESARIAL. A ÚNICA FINALIDADE DESTE PROGRAMA É PARA TESTES E ESTUDOS. --- !!

TurboClean é um projeto criado em Java. É um programa de computador p/Gerenciamento básico de Lava-Jatos, possuindo 4 telas: Registro, Login, Criar serviço e Detalhes de srrviço. Possui as operações do CRUD.

Esse projeto utiliza a estrutura MVC.
Abaixo segue a estrutura:
───────────────────────────────────────────────────────────────────────────────────────────────────────────────
com.turboclean
── controllers
   ── CreateServiceController.java
   ── HomeController.java
   ── LoginController.java
   ── RegisterController.java
   ── ServiceDetailsController.java
── db
   ── Database.java
── models
   ── Service.java
   ── User.java
── services
   ── ServiceService.java
   ── UserService.java
── Main.java

- Controllers: Gerenciam a interação do usuário com a interface gráfica. Cada controlador é responsável por uma parte específica da interface(FXML).
- db: Centraliza a lógica de conexão com o banco de dados
- Models: Representam as entidades do domínio, encapsulando os dados e fornece, métodos para acessar e modificar os dados.
- services: Contêm a lógica de funcionamento do código, interage com o banco de dados e manipulando os modelos.
───────────────────────────────────────────────────────────────────────────────────────────────────────────────
Versões utilizadas:
JDK - Java19
SDK - JavaFX 19.0.2.1
Scene Builder para criação de interface
Drivers MySql - Mysql Connector-j 8.4.0
───────────────────────────────────────────────────────────────────────────────────────────────────────────────
Criado por: Juan Guilherme
