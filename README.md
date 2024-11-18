# README: Análisis de Colegios Nuevos

## Propósito

Este script permite analizar y procesar datos de colegios a partir de un archivo Excel llamado `<span>padron_oficial.xlsx</span>`. Utiliza Python y herramientas de manipulación de datos como pandas para extraer, transformar y visualizar información clave. Es útil para estudios educativos, gestión de datos escolares y generación de reportes.

## Características principales

1. Carga datos desde un archivo Excel especificado.
2. Realiza inspecciones iniciales como:
   * Visualización de las primeras filas.
   * Conteo de registros.
   * Identificación de nombres de columnas.
3. Realiza transformaciones y cálculos sobre el dataset.
4. Exporta resultados procesados, si es necesario.

## Requisitos

* Python 3.10 o superior.
* Librerías:
  * pandas
  * numpy
  * openpyxl

Puedes instalar estas dependencias usando:

```
pip install pandas numpy openpyxl
```

## Archivos necesarios

1. `<span>padron_oficial.xlsx</span>`: Archivo Excel que contiene los datos a procesar.
   * **Nombre de la hoja**: "Padrón"
   * **Formato esperado**: El dataset comienza en la fila 6 (se omiten las primeras 5 filas al cargar).

## Instrucciones de uso

1. Coloca el archivo `<span>padron_oficial.xlsx</span>` en la misma carpeta que este script.
2. Ejecuta el script utilizando un entorno de Python compatible (como Jupyter Notebook o una terminal).
3. Los resultados del análisis se mostrarán en pantalla o se exportarán según lo configurado.

### Ejecución en Jupyter Notebook

Abre el notebook y ejecuta las celdas una por una para visualizar los pasos del análisis y sus resultados.

### Ejecución en terminal

Si decides convertir el notebook en un script Python (.py):

```
python colegiosNuevos.py
```

## Resultados esperados

* Visualización de las primeras filas del dataset.
* Información sobre el tamaño y estructura de los datos.
* Procesamiento de columnas clave y transformaciones aplicadas.
* Exportación de datos procesados (opcional).

## Estructura del proyecto

```
colegiosNuevos.ipynb  # Notebook principal con el código
padron_oficial.xlsx    # Archivo de entrada con los datos
```

## Contribución

Si deseas contribuir o reportar problemas, por favor abre un issue o envía un pull request en el repositorio correspondiente.

## Autor

Este script fue desarrollado para la gestión y análisis de datos educativos. Contacta al autor para más detalles o soporte.
