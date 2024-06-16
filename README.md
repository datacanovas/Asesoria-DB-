# 🚩 Introdución

El objetivo del proyecto fue diseñar y crear una base de datos para una empresa de asesoría, implementando un modelo estrella que permite realizar análisis de negocio complejos. 

Este modelo facilita la obtención de información clave sobre el desempeño del negocio, la productividad de los asesores, y la rentabilidad de los servicios prestados.

# 🚩 Diseño del Modelo de Datos

## 👉 Tablas de Dimensiones:

Dim_Fecha: Contiene detalles de la fecha del servicio, como año, trimestre, mes y día.

Dim_Cliente: Incluye información sobre los clientes, como nombre, empresa, industria, ubicación y contacto.

Dim_Asesor: Almacena datos sobre los asesores, como nombre, especialización, años de experiencia, correo y teléfono.

Dim_Area_Asesoria: Describe las diferentes áreas de asesoría ofrecidas, con nombre y descripción.


## 👉 Tabla de Hechos:

Fact_Servicios_Prestados: Registra cada servicio prestado, incluyendo referencias a las tablas de dimensiones (fecha, cliente, asesor, área de asesoría), y datos como horas trabajadas, tarifa por hora y costo total del servicio.


# 🚩 Diagrama de tablas 

Definimos la estructura de las tablas en un modelo relacional.

![image](https://github.com/datacanovas/Asesoria-DB-/assets/157279064/3e622586-007a-4254-81a6-3e4ea8aa7657)


# 🚩 Creación de la Base de Datos

1. Definición del esquema: Se definieron las estructuras de las tablas, asegurando las relaciones mediante claves foráneas y asegurando la integridad referencial.

2. Población de datos: Se generaron datos ficticios para poblar las tablas de dimensiones y la tabla de hechos, creando un conjunto de datos coherente y suficiente para análisis.



# 🚩 Análisis y Consultas

Con la base de datos poblada, se plantearon y resolvieron preguntas de negocio clave, tales como:

👉 Ingresos por Área de Asesoría: Se determinó cuánto ingreso generó cada área de asesoría durante el año.

👉 Productividad de los Asesores: Se identificaron los asesores con más horas de trabajo en determinados periodos.

👉 Ingresos por Cliente: Se analizó cuáles clientes generaron más ingresos para la empresa.

👉 Distribución Mensual de Ingresos: Se evaluó cómo se distribuyen los ingresos por área de asesoría mes a mes.

Si quieres acceder a las queries 

(https://github.com/datacanovas/Asesoria-DB-/blob/main/Asesoriadb.ipynb)
