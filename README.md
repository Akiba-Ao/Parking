# Parking Management System based on JavaWeb

  - [Attention](#attention)
  - [Introduction](#introduction)
    - [Characteristics:](#characteristics)
  - [Running Environment](#running-environment)
  - [Feasibility](#feasibility)
## Attention 
Please change content of .\src\DBUtil\db.properties
No.2 row `user` and `pwd` to your own MySQL Server user and pwd

If your MySQL version is lower than 5, please change content of .\src\DBUtil\db.properties
No.4 row to `driver=com.mysql.jdbc.Driver`
## Introduction

This is a simple Parking Management System based on JavaWeb technology

### Characteristics

1.Optimization of dynamic processing

2.Information protection and authority management

3.This system uses B/S structure, namely browser and server structure. Without downloading any software, users can quickly complete various operations directly on the browser side, which can meet users' needs for easy access to the system.

4.The system is developed using MVC framework, which has the characteristics of low coupling, high reusability, fast deployment and high maintainability, and can meet the needs of users for system stability.

5.The back-end code of this system uses Java language, which benefits from its language characteristics. 

## Running Environment

- Tomcat 9.0
- Java 1.8.0
- MySQL 8.0.24 Community

## Feasibility

- ### Economic feasibility

It is mainly to evaluate the economic benefits of developing the system. The system is developed with IntelliJ idea ultimate tool, the background database is MySQL community version, and the server is built with Apache Tomcat 9. In addition, there is no need to download other software for assistance. The above software can be obtained for free in the case of non-commercial use, reducing the cost of the system development.

- ### Social feasibility

The development of intelligent parking lot management system provides corresponding support for the future new energy vehicles to enter the market. Moreover, with the gradual improvement of urban road planning in recent years, the intelligent parking lot plays a very important role in it. It can improve the traffic flow speed, facilitate the travel of citizens, and also provide auxiliary support for the further construction plan of the city.

- ### Technical feasibility

This system is developed using JetBrains IntelliJ idea Ultimate 2022.1. Multi end applications are developed in a unified manner. The front-end and back-end functions are developed on this tool, which is low in technical difficulty and easy to use.
In the product design of the parking lot system, the product design model of MVC (model view control) implements the whole system, and the overall framework adopts the combined architecture of Spring MVC+JDBC.
The MVC design model is used in the product design of the parking lot management system to facilitate the developers to design the code. Because these three logics can be implemented together, the work efficiency is increased and the design time is saved. Moreover, due to the hierarchical design, the code is separated, which is more convenient for the developers to use.