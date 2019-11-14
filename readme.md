# SQL

SQL es el lenguaje de programación para las base de datos.

## Herramientas

Existe varias herramientas para controlar SQL por ejemplo:
* PostgreSQL
* MySQL
* SQLServer

## Consultas

La programación de SQL esta basado en consultas. Tenemos los diferentes tipos:
* SELECT
* INSERT
* UPDATE 
* DELETE

### Select

Esta consulta nos permite obtener resultados de toda una tabla o en especifico
Ejemplos:

**SELECCIONAR TODAS EL CONTENIDO DE UNA TABLA**
```sql
SELECT * FROM tabla;
```

| id | campo1 | campo2 | campo3 | campo4 |
|----|--------|--------|--------|--------|
| 1  | valor1 | valor2 | valor3 | valor4 |
| 2  | valor1 | valor2 | valor3 | valor4 |
| 3  | valor1 | valor2 | valor3 | valor4 |

**SELECCIONAR TODOS EL CONTENIDO DE UNA TABLA PERO ESPECIFICANDO LOS CAMPOS A OBTENER**
```sql
SELECT campo1, campo2 FROM tabla;
```

| campo1 | campo2 |
|--------|--------|
| valor1 | valor2 |
| valor1 | valor2 |
| valor1 | valor2 |

### INSERT

Esta consulta nos permite agregar fila(s) a una tabla.
Ejemplo:

**AGREGAR UNA FILA**
```sql
INSERT INTO tabla (campo1, campo2, campo3, campo4) VALUES ('valor1', 'valor2', 'valor3', 'valor4');
```

**AGREGAR VARIOS ELEMENTOS**
```sql
INSERT INTO tabla (campo1, campo2, campo3, campo4) VALUES ({'valor1', 'valor2', 'valor3', 'valor4'});
```
