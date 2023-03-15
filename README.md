# Resolviendo problemas con la librería Pandas.

## Setup

Instalar Jupyter Notebook: https://jupyter.readthedocs.io/en/latest/install.html <br/>
Instalar Pandas library: https://pandas.pydata.org/pandas-docs/stable/install.html 

## Background Information:

Este repo fue creado utilizando la guía del siguiente video de Youtube [my video](https://youtu.be/eMOA1pPVUc4) on "Solving real world data science videos with Python Pandas!".

En este video usamos Python Pandas & Python Matplotlib para analizar y responder preguntas sobre data anual de un negocio. Los datos corresponden a cientos de miles de ventas en una tienda electrónica.

Primero se limpió la data:
- Se eliminaron los valores NaN del DataFrame
- Se removieron filas con datos erróneos (Or)
- Se cambiaron los tipos de columnas (to_numeric, to_datetime, astype)

Luego de que limpiamos la data, respondimos las siguientes 5 preguntas:

-Cuál fue el mejor mes de ventas? Cuánto se ganó ese mes?
-Qué ciudad fue en la que se vendieron más productos?
- A qué hora deberíamos mostrar publicidad basándonos en los horarios de compra de los clientes?
- Qué productos se venden juntos más seguido?
- Qué producto se vendió más? Por qué pensás que fue así?

Para responder esas preguntas utilizamos pandas & matplotlib, y los métodos que usamos fueron:
-Agregar columnas.
-Cambiar formato de celdas a strings para crear nuevas columnas (.str)
-Usar el método .apply()
-Usar groupby para realizar análisis más certeros
-Crear gráficos de barras y líneas para visualizar resultados.
-Detallar nuestros gráficos.

