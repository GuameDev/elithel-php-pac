# Pac de desarrollo cliente servidor

## Índice

- [Pac de desarrollo cliente servidor](#pac-de-desarrollo-cliente-servidor)
  - [Índice](#índice)
  - [Descripción](#descripción)
  - [Tecnologías](#tecnologías)
  - [Análisis funcional](#análisis-funcional)
    - [Login](#login)

## Descripción

Aplicación web que permita a sus **usuarios** actualizar la
información de los **productos** que tiene actualmente en stock en una tienda. Entre las funcionalidades principales encontramos:

- Un usuario **superadmin** podrá permitir o no si se **añaden, editan o borran los
productos**, además de ver a todos los usuarios de la aplicación.

- Una serie de **usuarios autorizados** que podrán **acceder al stock de productos** y, en caso de estar permitido por el superadmin, añadir productos, editarlos o borrarlos.

## Tecnologías

- Frontend y Backend
  - PHP
  - HTML
  - CSS
  
- Arquitectura
  - MVC
  
- Base de datos
  - MYSQL

## Análisis funcional
  
### Login

Autorización basada en usuario y contraseña y autenticación por los siguientes roles:

- SuperAdmin
  - Capaz de realizar operaciones **CRUD** sobre los **Productos** +ç
    - C => **Create** => **INSERT INTO** Products VALUES(value1, value2, value3, ...);
    - R => **Read** => **SELECT * FROM Products**
    - U => **Update** => **UPDATE Products SET column1 = value1 WHERE = condition**
    - D => **Delete** => **DELETE from Products**
  