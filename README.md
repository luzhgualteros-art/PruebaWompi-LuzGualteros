Proyecto de Analisis de transacciones aprobadas en formato json con vista agrupad en salida formato .parquet.

Requisitos:

Ingresar a google colab: https://colab.google/.

Archivo de entrada: 
transactions_50k.jsonl

Ejecución paso a paso con google colab:

1. Abrir google colab con una cuenta de gmail.
2. importar el notebook que se subio al Github 2_Reto_Practico_Wompi.ipynb
3. Subir el archivo de transactions_50k al drive de la cuenta de gmail.
4.Crear una nueva celda de codigo al inicio del notebook.
5.Identificar en que carpeta se encuentra el archivo cargado con el comando: !ls /content/drive/MyDrive
6.Luego colocar la ruta del archivo en la variable ruta que esta en la segunda celda del notebook.
7.En el menú superior, selecciona entorno de ejecución ---> Ejecutar todas
8.el notebook leera el archivo json , procesa los datos y genera un archivo parquet que queda en la carpeta 
de la parte izquierda del notebook, seleccionar descargar.
