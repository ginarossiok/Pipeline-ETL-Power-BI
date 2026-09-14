# Pipeline ETL - Power BI

Proyecto desarrollado como parte del curso de Data Analytics.

## Objetivo

Construir un pipeline ETL en Power BI utilizando Power Query para importar, perfilar, limpiar y transformar un conjunto de datos de ventas.

## Transformaciones realizadas

Se trabajó con cuatro tablas:

- Dim_Clientes
- Dim_Productos
- Dim_Categorias
- Fact_Ventas

Durante el proceso ETL se realizaron las siguientes transformaciones:

- Eliminación de filas vacías.
- Eliminación de registros duplicados mediante sus identificadores.
- Tratamiento de valores nulos.
- Asignación y corrección de tipos de datos.
- Imputación de un precio faltante utilizando la mediana de los precios válidos.
- Integración de nombre y categoría del producto en Fact_Ventas mediante Merge Queries.
- Renombrado de pasos de transformación para mejorar la trazabilidad.
- Documentación del código M mediante comentarios explicativos.

## Resultado final

El modelo quedó compuesto por:

- Dim_Clientes: 11 registros.
- Dim_Productos: 12 registros.
- Dim_Categorias: 4 registros.
- Fact_Ventas: 50 registros.

El archivo final de Power BI se encuentra disponible en este repositorio como:

`Pipeline_ETL_Rossi_Gina.pbix`
