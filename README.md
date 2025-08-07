# Instalación de PostgreSQL con Docker y conexión desde DataGrip

Este proyecto muestra el proceso para instalar PostgreSQL utilizando Docker y conectarlo desde DataGrip.

## Pasos realizados

1. Se instala Docker.
2. Se ejecuta el contenedor de PostgreSQL con el siguiente comando:

   ```bash
   docker run --name postgres-db -e POSTGRES_PASSWORD=12345 -p 5432:5432 -d postgres
   ```

3. Se instala y configura DataGrip para conectarse a la base de datos PostgreSQL.
4. Se crea una base de datos llamada `my_first_database` desde la consola de consultas SQL, ejecutando:

   ```sql
   CREATE DATABASE my_first_database;
   ```

---

## Capturas

Se incluyen capturas de evidencia.

---

**Autor:** César González  
**Carné:** 2890-23-17663