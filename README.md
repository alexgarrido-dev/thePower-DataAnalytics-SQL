# thePower-DataAnalytics-SQL

1. Título del Proyecto

Análisis de Datos de Videoclub: Proyecto SQL (Sakila)

2. Descripción

Este proyecto consiste en un análisis exhaustivo y la explotación de una base de datos relacional (Sakila) que simula el entorno de gestión de un videoclub. 

A través de la resolución de 64 consultas SQL progresivas, el objetivo es demostrar el dominio técnico del lenguaje SQL (desde selecciones básicas hasta subconsultas complejas, vistas y tablas temporales). Las consultas están orientadas a resolver problemas reales: gestión de inventario, análisis de comportamiento de clientes, optimización de marketing y control de facturación.

3. Estructura del Proyecto

El repositorio está compuesto por los siguientes archivos:

📁 Directorio_Raiz/

│

├── 📄 proyecto_consultas.sql   # Archivo principal con las 64 consultas

├── 🖼️ diagrama_tablas.png      # Diagrama Entidad-Relación (ER) de la BBDD

└── 📄 README.md                # Documentación del proyecto

4. Tecnologías y Herramientas utilizadas
   
- Motor de Base de Datos: PostgreSQL
- Gestor de Base de Datos (IDE): DBeaver
- Lenguaje: SQL

5. Resultados y Conclusiones

Durante la exploración y modelado de los datos, se extrajeron insights fundamentales para la toma de decisiones del videoclub, destacando:

- Segmentación de Clientes: Identificación de "Clientes VIP" por volumen de gasto.
- Estado del Inventario: Detección de películas altamente rentables, análisis de varianza en los costes de reemplazo y control de productos retenidos por clientes fuera de plazo.
- Rendimiento del Catálogo: Mapeo de los géneros más alquilados y actores más demandados, proporcionando una guía clara para la futura adquisición de stock (ej. fortalecimiento del catálogo de Acción y Animación).
- Limpieza de Datos: Auditoría del sistema que confirmó la ausencia de registros huérfanos (ej. actores sin películas vinculadas).

6. Próximos Pasos
   
- Exportar los conjuntos de datos generados por las vistas SQL (como el total de alquileres por cliente) a herramientas de visualización para crear un dashboard interactivo.

7. Autores y Agradecimientos
   
Alex Garrido
@alexgarrido_dev
