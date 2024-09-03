En este proyecto, se utilizó BeautifulSoup, Selenium, y Pandas para realizar web scraping de una página de ofertas en Mercado Libre. El objetivo era extraer información relevante de los productos listados, incluyendo nombres, precios, y descuentos , para su posterior análisis y almacenamiento en un DataFrame de Pandas.

Selenium: Se utilizó Selenium para interactuar con la página web de manera dinámica. Esto incluyó la navegación a través de varias páginas (paginación) hasta la página 20, y la simulación de acciones del usuario, como hacer clic en los botones de "siguiente página".

BeautifulSoup: Una vez cargada la página con Selenium, se empleó BeautifulSoup para analizar el contenido HTML y extraer los datos deseados, como nombres de productos y precios.

Pandas: Los datos extraídos se almacenaron en un DataFrame de Pandas, lo que permitió un análisis estructurado y la posibilidad de exportar los datos a formatos como CSV para su posterior uso.

Comandos para instalar las librerías:

Si no tienes instaladas estas librerías, puedes hacerlo usando pip con los siguientes comandos:

pip install beautifulsoup4

pip install selenium

pip install pandas
