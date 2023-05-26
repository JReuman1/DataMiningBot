# Data Mining Bot

## Descripción

Este es un script de Python que utiliza Selenium y BeautifulSoup para extraer información relevante de las primeras 100 páginas de resultados de búsqueda de Google. El script busca información relacionada con una lista de ciudades y una lista de hashtags, principalmente asociados con criptomonedas. La información extraída es almacenada en un CSV para su posterior análisis.

## Pre-requisitos

Antes de poder ejecutar este script, necesitarás tener instalado lo siguiente:

- Python 3.6 o superior
- Selenium
- BeautifulSoup
- pandas
- geckodriver (para Firefox)

Todas las bibliotecas de Python pueden ser instaladas con pip:

-  `pip install selenium beautifulsoup4 pandas `

El Geckodriver se debe instalar y ubicar en una ruta accesible por el sistema. Puedes encontrar las instrucciones detalladas [aquí](https://github.com/mozilla/geckodriver).

## Uso

Para ejecutar el script, simplemente corre el archivo .py en la línea de comandos:

- ` python script.py `


El script generará un archivo CSV con los resultados de la búsqueda. Los resultados son almacenados en formato de texto sin formato.

## Personalización

Puedes personalizar la búsqueda modificando las listas de ciudades (`places`) y hashtags. También puedes cambiar la expresión regular (`regex`) para adaptarse a la información que quieres extraer de los resultados.

El script actualmente está configurado para buscar en el sitio `YOUR_SITE.com`, y esto puede ser cambiado para buscar en cualquier sitio que prefieras. Asimismo, puedes ajustar la demora entre las consultas de búsqueda para adaptarte a las políticas de tu motor de búsqueda.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre una issue para discutir lo que te gustaría cambiar o añadir.



