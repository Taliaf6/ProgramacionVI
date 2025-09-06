# ProgramacionVI
** API REST con .NET Core**

## 📌 Descripción General

Este proyecto consiste en el desarrollo de una **API REST utilizando .NET Core Web API**, orientada a demostrar el dominio de arquitectura de software, servicios web y persistencia de datos. La solución implementa al menos una de las operaciones CRUD (Create, Read, Update, Delete), también conocidas como ABCC (Altas, Bajas, Cambios y Consultas), sobre una base de datos relacional.

La aplicación está diseñada para que los **controladores interactúen exclusivamente con servicios internos**, respetando el principio de separación de responsabilidades. La base de datos utilizada **no es accesible directamente** por aplicaciones externas, garantizando que toda interacción se realice a través del servicio REST.


## Operaciones CRUD Implementadas

La API implementa al menos una de las siguientes operaciones:

- **Create (Alta)**: Registro de nuevas entidades  
- **Read (Consulta)**: Recuperación de datos específicos o listados  
- **Update (Cambio)**: Modificación de registros existentes  
- **Delete (Baja)**: Eliminación lógica o física de registros

## 🧩 Arquitectura de la Solución

```plaintext
[Cliente/API Consumer]
        ↓
[Controlador] → [Servicio] → [Repositorio] → [Base de Datos]

