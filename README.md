# ✈️ Proyecto 4: SQL - Análisis de Base de Datos de Vuelos

![SQL](https://img.shields.io/badge/SQL-Relational-blue?style=for-the-badge&logo=postgresql)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![pgAdmin4](https://img.shields.io/badge/pgAdmin4-336791?style=for-the-badge&logo=postgresql&logoColor=white)

Este repositorio contiene la resolución técnica del **Proyecto 4 de SQL**, enfocado en la extracción y análisis de datos de una base de datos de reservas aéreas. A través de diversas consultas, se exploran habilidades de organización de información y comunicación visual para obtener resultados precisos y eficientes.

---

## 🎯 Objetivo del Proyecto

El propósito de este proyecto es realizar diversas **operaciones de lectura** (SELECT) para consultar información específica sobre vuelos, aeropuertos, modelos de aviones y tickets de pasajeros. He adaptado cada consulta a la estructura real de la base de datos instalada para garantizar resultados precisos y eficientes.

---

## 🛠️ Instalación y Configuración

Para replicar este entorno de trabajo, se utilizó la base de datos demo proporcionada por **PostgresPro**:

* **URL de descarga**: [PostgresPro Demo Database](https://postgrespro.com/docs/postgrespro/current/demodb-bookings-installation.html).
* **Comando de instalación**: 
    `psql -f demo_small_YYYYMMDD.sql -U postgres`.
* **Herramientas**: **pgAdmin 4** para la ejecución de queries y **VSCode** para la organización del código.

---

## 📊 Ejercicios y Consultas Realizadas

A continuación, se presenta un resumen de los retos resueltos en el archivo `IntroBBDD.sql`:

| # | Desafío Técnico | Concepto SQL Aplicado |
| :--- | :--- | :--- |
| **01** | Recuperar vuelos con estado **'On Time'** | Filtrado con `WHERE` |
| **02** | Reservas con importe total **> 1,000,000** | Operadores de comparación |
| **03** | Extraer datos de los **modelos de aviones** | Selección total de columnas (`SELECT *`) |
| **04** | Identificadores de vuelos con **Boeing 737** | Subconsultas (`IN`) |
| **05** | Tickets comprados por pasajeros llamados **"Irina"** | Patrones de texto con `LIKE` |
| **06** | Ciudades con **más de un aeropuerto** | Agrupación con `GROUP BY` y `HAVING` |
| **07** | Número de vuelos por **modelo de avión** | Unión de tablas con `JOIN` |
| **08** | Reservas con **múltiples pasajeros** | Funciones de agregado (`COUNT`) |
| **09** | Vuelos con retraso superior a **una hora** | Aritmética de fechas y `INTERVAL` |

---

## 📂 Estructura del Repositorio

* `IntroBBDD.sql`: Contiene todas las sentencias SQL ejecutadas y validadas.
* `README.md`: Descripción detallada del proyecto (este archivo).

---

## ✒️ Autor

**Sergio Valiente**
* [Perfil de GitHub](https://github.com/servado07)

---
*Este proyecto forma parte del Máster en Ciberseguridad (UCAM) / ThePower Pometeo.*
