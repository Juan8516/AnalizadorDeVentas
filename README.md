Objetivo

Este programa en Python analiza un conjunto de datos de ventas de una tienda. El programa realiza varias operaciones de Data Science para proporcionar información sobre las ventas de la tienda.
Detalle

    Lectura de Datos: Se crea un DataFrame que contiene los datos provistos en el archivo Datos_Ventas_Tienda.csv. El archivo incluye información como fecha de venta, categoría de producto, cantidad vendida y precio.
    Fusión de Datos: Se crea un segundo DataFrame qque contiene los datos del archivo Datos_Ventas_Tienda2.csv. Se concatenan para tener un solo dataFrame con toda la información.
    Tratamiento de Datos: Se utiliza Pandas para manipular estos datos. Se utilizan tareas como limpieza de datos, filtrado y transformaciones básicas.
    Análisis de Ventas: Se realiza análisis para responder a preguntas como:

    ¿Cuál es el producto más vendido?
    ¿Cuál es el mes con más ventas?

    Datos Agrupados: Se agrupan los datos por categoría de producto y analiza las ventas por categoría.
    Guardar Resultados: Al final, se guarda el DataFrame completo (incluyendo la columna de meses) en un archivo .csv en el ordenador.
