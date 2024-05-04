# LAB | Java SQL

## Introducción

Acabamos de aprender cómo normalizar bases de datos así como cómo crear esquemas de base de datos y cómo realizar consultas SQL complejas, así que practiquemos un poco más.

<br>

## Requisitos

1. Haz un fork de este repositorio.
2. Clona este repositorio.
3. Añade a tu instructor y a los calificadores de la clase como colaboradores de tu repositorio. Si no estás seguro de quiénes son los calificadores de tu clase, pregunta a tu instructor o consulta la presentación del primer día.
4. En el repositorio, crea un proyecto de Java y añade el código para las siguientes tareas.

## Entrega

Una vez que termines la tarea, envía un enlace URL a tu repositorio o tu solicitud de extracción en el campo de abajo.

<br>

## Instrucciones

1. Normalice la siguiente base de datos de blog y escriba los scripts DDL para crear las tablas de la base de datos:

| author          | title                       | word count | views |  
| --------------- | --------------------------- | ---------- | ----- |  
| Maria Charlotte | Best Paint Colors           | 814        | 14    |  
| Juan Perez      | Small Space Decorating Tips | 1146       | 221   |  
| Maria Charlotte | Hot Accessories             | 986        | 105   |  
| Maria Charlotte | Mixing Textures             | 765        | 22    |  
| Juan Perez      | Kitchen Refresh             | 1242       | 307   |  
| Maria Charlotte | Homemade Art Hacks          | 1002       | 193   |  
| Gemma Alcocer   | Refinishing Wood Floors     | 1571       | 7542  |  

<br>  

2. Normalice la siguiente base de datos de aerolíneas y escriba los scripts DDL para crear las tablas de la base de datos:

| Customer Name    | Customer Status | Flight Number | Aircraft    | Total Aircraft Seats | Flight Mileage | Total Customer Mileage |  
| ---------------- | --------------- | ------------- | ----------- | -------------------- | -------------- | ---------------------- |  
| Agustine Riviera | Silver          | DL143         | Boeing 747  | 400                  | 135            | 115235                 |  
| Agustine Riviera | Silver          | DL122         | Airbus A330 | 236                  | 4370           | 115235                 |  
| Alaina Sepulvida | None            | DL122         | Airbus A330 | 236                  | 4370           | 6008                   |  
| Agustine Riviera | Silver          | DL143         | Boeing 747  | 400                  | 135            | 115235                 |  
| Tom Jones        | Gold            | DL122         | Airbus A330 | 236                  | 4370           | 205767                 |  
| Tom Jones        | Gold            | DL53          | Boeing 777  | 264                  | 2078           | 205767                 |  
| Agustine Riviera | Silver          | DL143         | Boeing 747  | 400                  | 135            | 115235                 |  
| Sam Rio          | None            | DL143         | Boeing 747  | 400                  | 135            | 2653                   |  
| Agustine Riviera | Silver          | DL143         | Boeing 747  | 400                  | 135            | 115235                 |  
| Tom Jones        | Gold            | DL222         | Boeing 777  | 264                  | 1765           | 205767                 |  
| Jessica James    | Silver          | DL143         | Boeing 747  | 400                  | 135            | 127656                 |  
| Sam Rio          | None            | DL143         | Boeing 747  | 400                  | 135            | 2653                   |  
| Ana Janco        | Silver          | DL222         | Boeing 777  | 264                  | 1765           | 136773                 |  
| Jennifer Cortez  | Gold            | DL222         | Boeing 777  | 264                  | 1765           | 300582                 |  
| Jessica James    | Silver          | DL122         | Airbus A330 | 236                  | 4370           | 127656                 |  
| Sam Rio          | None            | DL37          | Boeing 747  | 400                  | 531            | 2653                   |  
| Christian Janco  | Silver          | DL222         | Boeing 777  | 264                  | 1765           | 14642                  |  

<br>  

3. En la base de datos de aerolíneas escriba el script SQL para obtener el número total de vuelos en la base de datos.
4. En la base de datos de aerolíneas escriba el script SQL para obtener la distancia promedio de vuelo.
5. En la base de datos de aerolíneas escriba el script SQL para obtener el número promedio de asientos.
6. En la base de datos de aerolíneas escriba el script SQL para obtener el número promedio de millas voladas por los clientes agrupados por estatus.
7. En la base de datos de aerolíneas escriba el script SQL para obtener el número máximo de millas voladas por los clientes agrupados por estatus.
8. En la base de datos de aerolíneas escriba el script SQL para obtener el número total de aeronaves con un nombre que contiene Boeing.
9. En la base de datos de aerolíneas escriba el script SQL para encontrar todos los vuelos con una distancia entre 300 y 2000 millas.
10. En la base de datos de aerolíneas escriba el script SQL para encontrar la distancia promedio de vuelo reservada agrupada por estatus de cliente (esto requerirá una unión).
11. En la base de datos de aerolíneas escriba el script SQL para encontrar la aeronave más a menudo reservada por los miembros de estatus de oro (esto requerirá una unión).

<br>  
