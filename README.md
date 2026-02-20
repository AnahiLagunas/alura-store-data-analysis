📊 Proyecto de Análisis de Optimización: AluraStore Latam

📝 Descripción del Proyecto
Este proyecto surge de la necesidad estratégica de optimizar la red de tiendas de AluraStore. El objetivo principal es identificar, mediante el análisis de datos con Python, cuál de las cuatro tiendas presenta el rendimiento más bajo en términos financieros y operativos. Este análisis servirá como base para que el Sr. Juan decida qué unidad vender para financiar una nueva inversión.
🛠️ Tecnologías y Dependencias
Para este análisis se utilizó el lenguaje Python 3 y las siguientes librerías de ciencia de datos:
•	Pandas: Para la manipulación, limpieza y análisis de los DataFrames.
•	Matplotlib / Seaborn: Para la creación de visualizaciones estadísticas y comparativas.

📁 Estructura de los Datos
El análisis procesa cuatro bases de datos en formato CSV (alojadas en GitHub), que contienen la siguiente información:
•	Producto y Categoría del Producto: Identificación de ítems vendidos.
•	Precio: Valor de venta (utilizado para el cálculo de facturación).
•	Costo de envío: Gasto logístico asociado a cada venta.
•	Calificación: Nivel de satisfacción del cliente (1-5).
•	lat / lon: Coordenadas geográficas del punto de venta/entrega.

🚀 Cómo ejecutar el análisis
1.	Abre el archivo .ipynb en Google Colab.
2.	Ejecuta la celda de Importación de datos para conectar con los repositorios remotos.
3.	Asegúrate de ejecutar la celda de Consolidación donde se crea la lista todas_las_tiendas para evitar errores de definición.
4.	Sigue el flujo de las 5 dimensiones de análisis y la sección de visualización final.
   
📈 Resumen de Resultados
•	Tienda recomendada para la venta: Tienda 4.
•	Razón principal: Menor facturación total ($1,038M) a pesar de tener los costos de envío más bajos, lo que indica una falta de rentabilidad por volumen o margen de productos.
•	Hallazgo Geográfico: Las ventas se concentran en zonas donde la competencia interna es alta, no justificando el mantenimiento de una cuarta sucursal.
