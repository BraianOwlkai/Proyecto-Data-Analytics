# RetailPro — Proyecto de Análisis de Datos

## Descripción del proyecto

RetailPro es un proyecto de análisis de datos orientado al estudio de información comercial mediante consultas SQL y herramientas de análisis y visualización. El objetivo es organizar los datos de ventas, obtener indicadores relevantes y generar información útil para la toma de decisiones.

El proyecto utiliza la base de datos `Ventas_Tech_DB`, que contiene información sobre ventas, clientes, productos y categorías.

## Objetivos

- Analizar la facturación y las ventas.
- Examinar los productos según las unidades vendidas y los ingresos generados.
- Obtener indicadores como el ticket promedio.
- Analizar las relaciones entre ventas, clientes, productos y categorías.
- Documentar los procedimientos y resultados del proyecto.

## Herramientas utilizadas

- **SQL:** consultas para analizar datos comerciales y relacionar tablas.
- **Power BI:** archivos de trabajo y análisis mediante modelos de datos y medidas.
- **Power Query:** herramienta utilizada en el proceso de preparación y transformación de datos.

El motor de base de datos, su versión y el cliente SQL utilizado deben confirmarse antes de documentar instrucciones específicas de ejecución.

## Estructura del repositorio

Los siguientes archivos se encuentran en el repositorio:

| Archivo | Descripción |
|---|---|
| `ventas_tech_db.sql` | Script relacionado con la base de datos. |
| `m4_consultas_negocio.sql` | Consultas de análisis de negocio. |
| `m5_consultas_joins.sql.sql` | Archivo de consultas SQL que trabajan con relaciones entre tablas. |
| `Diaz_Braian_Checkpoint2.pbix` | Archivo de Power BI correspondiente al checkpoint. |
| `Diaz_Braian_Checkpoint2.pdf` | Documento PDF de presentación del checkpoint. |
| `Pipeline_ETL_Diaz_Braian.pbix.pbix` | Archivo del proyecto ETL según el nombre registrado en el repositorio. |

Los nombres se muestran tal como aparecen en GitHub.

## Modelo de datos

La base de datos `Ventas_Tech_DB` contempla las siguientes tablas:

- **categorias:** información de las categorías de productos.
- **clientes:** información de los clientes.
- **productos:** información de los productos, sus categorías, precios y stock.
- **ventas:** registros de ventas, con datos de clientes, productos, cantidades, precios unitarios y fechas.

Las relaciones entre las tablas permiten vincular las ventas con los clientes y productos, y los productos con sus categorías.

## Análisis realizados

Las consultas SQL de M4 contemplan:

- Facturación por período.
- Cantidad de registros de ventas y ticket promedio.
- Productos con mayor facturación.
- Unidades vendidas por producto.
- Clientes con más de un registro de venta.
- Comparación de la facturación mensual con el promedio mensual.

Las consultas de M5 incluyen uniones entre tablas para consolidar información comercial y consultas para identificar clientes y productos sin ventas, entre otros análisis.

## Cómo utilizar el proyecto

1. Clonar o descargar el repositorio de GitHub.
2. Revisar el contenido de `ventas_tech_db.sql` para conocer la creación y carga de las tablas.
3. Revisar `m4_consultas_negocio.sql` para identificar las consultas de análisis comercial.
4. Revisar `m5_consultas_joins.sql.sql` para examinar las consultas que relacionan distintas tablas.
5. Ejecutar los scripts en un entorno SQL compatible con la sintaxis utilizada en cada archivo.
6. Abrir los archivos `.pbix` con Power BI Desktop para revisar los modelos y análisis incluidos.

**Importante:** antes de ejecutar los scripts, verificá el motor SQL y la sintaxis compatible. Los archivos deben revisarse para confirmar el orden de ejecución y las dependencias entre ellos. No se especifica un comando único de ejecución porque el entorno y la compatibilidad del motor todavía deben confirmarse.

## Criterios de análisis

Los resultados deben interpretarse en función de los datos disponibles y las reglas de negocio del proyecto. Las hipótesis comerciales requieren validación adicional antes de convertirse en conclusiones definitivas.

Las consultas, los modelos y las medidas deben verificarse para asegurar que los indicadores representen correctamente la información analizada.

## Estado de la documentación

Este README documenta la estructura y los objetivos identificados del proyecto. Los detalles del entorno SQL, las versiones de las herramientas y las instrucciones específicas de configuración quedan pendientes de confirmación.

## Licencia

No se ha especificado una licencia para este repositorio.
