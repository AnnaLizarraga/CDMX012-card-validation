- [Español](#-Índice)
- [English](#-Index)

***

![Shows CRUD functionalities](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/gif_Card_Validation.gif)

Project Deploy:
In process...

***
# Validación de tarjeta prepago Spotify Premium.

## Índice

- [1. Resumen del proyecto](#1-resumen-del-proyecto)
- [2. Tech Skills del Proyecto](#2-Tech-Skills-del-Proyecto)
- [3. Planeación](#3-Planeación)
- [4. Investigación UX](#4-Investigación-UX)
- [5. Bocetaje + Prototipo + Feedback ](#5-Bocetaje-+-Prototipo-+-Feedback-de-iteración)

***
## 1. Resumen del proyecto

En este proyecto se llevará acabo el desarrollo de una interfaz de una aplicación web en la cual se validarán los dígitos de una tarjeta mediante el algoritmo de Luhn implementado mediante JavaScript, Además de implementar la funcionalidad para ocultar todos los dígitos de dicha tarjeta menos los últimos cuatro ya que son datos sensibles del usuario.

Este algoritmo es simple. Obtenemos la reversa del número a verificar (que solamente contiene dígitos [0-9]); a todos los números que ocupan una posición par se les debe multiplicar por dos, si este número es mayor o igual a 10, debemos sumar los dígitos del resultado; el número a verificar será válido si la suma de sus dígitos finales es un múltiplo de 10.

***
## 2. Tech Skills del Proyecto

### HTML 5 
- Semántico

### CSS 
- Selectores de CSS
- Box Model

### Web APIs
- Uso de selectores del DOM
- Manejo de eventos del DOM
- Manipulación dinámica del DOM

### JavaScript Vanilla
- Datos primitivos
- Strings
- variables
- Funciones
- Condicionales
- Bucles/ciclos
- Módulos de ECMAScript.

### Control de versiones Git- Github
- Init, clone, add, commit, status, push, pull, remote, checkout
- GitHub: Despliegue con GitHub Pages.

***
## 3. Planeación
Este proyecto se realizó con metodologías agiles SCRUM en 2 sprints de 1 semana en la cual se trabajaron historias de usuario.

Puedes ver la planeación [aquí](https://github.com/AnnaLizarraga/CardValidation-Spotify/projects/1?fullscreen=true)

### Historia de Usuario 1: Validar Tarjeta.

La interfaz debe permitir al usuario:

-	Ingresar el número que queremos validar.
-	No debe poder ingresar un campo vacío.
-	Mostrar un alert si es un número de tarjeta inválido.
-	Redirigir en caso de ser válido.

### Historia de Usuario 2: Maskify.

La interfaz debe permitir al usuario:

-	Ocultar todos los dígitos de su número de tarjeta menos los últimos 4 caracteres.

***
## 4. Investigación UX

### ¿Quiénes son los usuarios de este producto?

Los usuarios de esta herramienta son principalmente jóvenes “Milenials” (72%) que utilizan la aplicación de streaming de música Spotify, con este producto se soluciona un problema que presentan los usuarios, el pago de la suscripción.

### ¿Cómo soluciona los problemas de los usuarios este producto?

La mayoría de los usuarios han reflejado que no se sienten cómodos domiciliando sus pagos a sus cuentas de tarjetas, ya sea por la incertidumbre que genera el ingresar datos bancarios en aplicaciones, tener pagos recurrentes fijos sin una previa confirmación, aumento de costos sin previo aviso o simplemente porque no cuentan con una tarjeta, ya que un 32% de los usuarios son menores de edad. Con esta tarjeta de prepago, se domicilia a la cuenta spotify del particular y cuentas asociadas, así se tiene más control de los pagos a la aplicación de streaming, los usuarios pueden depositar o transferir directamente el monto concreto de mensualidad (membresía individual, duo, plan familiar o estudiantes) y tener el control total de sus gastos. A diferencia de las tarjetas de regalo que hay en la actualidad, esta tiene la ventaja de estar directamente a la cuenta del usuario y se puede recargar de manera más fácil, una vez asociada y validada la tarjeta en la cuenta, se puede seleccionar como método de pago desde la app, además de contar con promociones exclusivas para miembros recurrentes.

***
## 5. Bocetaje + Prototipo + Feedback de iteración

### Resumen del feedback

En el feedback se sugirió que la función de enmascarado se mostrara en el input / tarjeta para tener cubiertos los datos al momento de ser ingresados por cuestiones de privacidad del usuario.

### Boceto

![Fig 1. Boceto](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Boceto%20card%20validation.JPG)
Fig 1. Boceto

### Prototipo final

![Fig 2. Prototipo pantalla principal](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Principal_Empty.jpg)
Fig 2. Prototipo pantalla principal

![Fig 3. Prototipo pantalla datos ingresados](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Principal_Data.jpg)
Fig 3. Prototipo pantalla datos ingresados

![Fig 4. Prototipo pantalla alerta / hovers / reverso tarjeta](https://github.com/AnnaLizarraga/CardValidation-Spotify/blob/main/src/recursos%20v/Prototipo/Principal_Alerts.jpg)
Fig 4.Prototipo pantalla alerta / hovers / reverso tarjeta


***
# Card validation | Spotify Premium prepaid.

## Index
- [1. Project Summary](#1-Project-Summary)
- [2. Project Tech Skills](#2-Tech-Skills-project)
- [3. Planning](#3-Planning)
- [4. UX-Research](#4-UX-Research)
- [5. Sketching + Prototyping + Feedback](#5-Sketching-+-Prototyping-+-Prototyping-+-Feedback-of-iteration)

***
## 1. Project Summary

In this project will be carried out the development of a web application interface in which the digits of a card will be validated by Luhn's algorithm implemented through JavaScript, in addition to implementing the functionality to hide all the digits of the card except the last four as they are sensitive user data.

This algorithm is simple. We obtain the reverse of the number to verify (which only contains digits [0-9]); all numbers occupying an even position must be multiplied by two, if this number is greater than or equal to 10, we must add the digits of the result; the number to verify will be valid if the sum of its final digits is a multiple of 10.

***
## 2. Project Tech Skills

### HTML 5 
- Semantics

### CSS 
- CSS Selectors
- Box Model

### Web APIs
- Using DOM selectors
- DOM Event Handling
- Dynamic DOM Manipulation

### JavaScript Vanilla
- Data primitives
- Strings
- variables
- Functions
- Conditionals
- Loops/cycles
- ECMAScript modules.

### Git version control - Github
- Init, clone, add, commit, status, push, pull, remote, checkout
- GitHub: Deployment with GitHub Pages.

***
## 3. Planning

This project was done with SCRUM agile methodologies in 2 sprints of 1 week in which user stories were worked.

You can see the planning [here](https://github.com/AnnaLizarraga/CardValidation-Spotify/projects/1?fullscreen=true)

### User Story 1: Validate Card.

The interface must allow the user to:

- Enter the number we want to validate.
- You should not be able to enter an empty field.
- Show an alert if it is an invalid card number.
- Redirect if it is valid.

### User Story 2: Maskify.

The interface should allow the user to:

- Hide all but the last 4 characters of their card number.

***
## 4. UX-Research

### Who are the users of this product?

The users of this tool are mainly young "Millenials" (72%) who use the music streaming application Spotify, with this product we solve a problem that users present, the payment of the subscription.

### How does this product solve user's problems?

The majority of users have reflected that they do not feel comfortable direct debiting their payments to their card accounts, either because of the uncertainty generated by entering bank details in applications, having fixed recurring payments without prior confirmation, cost increases without prior notice or simply because they do not have a card, since 32% of users are minors. With this prepaid card, the card is direct debited to the individual's Spotify account and associated accounts, so there is more control of payments to the streaming application, users can deposit or transfer directly the specific amount of monthly payment (individual membership, duo, family or student plan) and have full control of their expenses. Unlike current gift cards, this one has the advantage of being directly linked to the user's account and can be recharged more easily, once the card is associated and validated in the account, it can be selected as a payment method from the app, in addition to exclusive promotions for recurring members.

***
## 5. Sketching + Prototyping + Feedback of iteration
In the feedback it was suggested that the masking function be shown on the input / card to have the data covered at the time of entry for user privacy issues.

### Sketch

![Fig 1. Sketch](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Boceto%20card%20validation.JPG)
Fig 1. Sketch

### Final prototype

![Fig 2. Prototype main screen](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Principal_Empty.jpg)
Fig 2. Prototype main screen

![Fig 3. Prototype of the input data screen](https://raw.githubusercontent.com/AnnaLizarraga/CardValidation-Spotify/main/src/recursos%20v/Prototipo/Principal_Data.jpg)
Fig 3. Prototype input data screen

![Fig 4. Prototype alert screen / hovers / back of card](https://github.com/AnnaLizarraga/CardValidation-Spotify/blob/main/src/recursos%20v/Prototipo/Principal_Alerts.jpg)
Fig 4. Prototype alert / hovers / back of card screen

