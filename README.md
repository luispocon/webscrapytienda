# __Web Scraping Project__
Este proyecto de web scraping está diseñado para extraer información de productos y precios del sitio de Kemik, específicamente de la categoría de tecnología. Utiliza requests y BeautifulSoup para la extracción de datos, y pandas para procesar y manipular la información. 

## __Características__
* Extracción de títulos de productos y sus precios.
* Identificación de precios de oferta y precios normales.
* Cálculo del porcentaje de descuento para cada producto.
* Exportación de los datos extraídos a un archivo de Excel.
## __Requisitos__
Este proyecto requiere las siguientes librerías de Python:

* requests: Para realizar solicitudes HTTP y obtener el contenido HTML.
* beautifulsoup4: Para parsear y extraer información del HTML.
* pandas: Para manipular y estructurar los datos extraídos.
* lxml (opcional): Parser de HTML más rápido que html.parser.
