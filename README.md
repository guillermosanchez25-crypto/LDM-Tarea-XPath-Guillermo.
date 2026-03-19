# LDM-Tarea-XPath-Guillermo.

Responde a los siguientes retos en tu XPath Notebook.
Reto 1: Filtrado por contenido y estado. El departamento de desarrollo necesita actualizar su bibliografía sobre diseño. Obtén los títulos de todos los recursos cuya categoría sea 'CSS' y que, además, estén marcados como disponibles (true).
Reto 2: Atributos y negaciones. No todos nuestros recursos son documentos estándar. Queremos identificar aquellos materiales que tienen un formato especial. Selecciona los ID (el atributo id) de todos los recursos cuyo formato no sea "PDF".
Reto 3: Manejo de múltiples nodos (Autores). La colaboración es clave en la ciencia. Localiza y muestra únicamente el nombre del primer autor de aquellos recursos que han sido publicados después del año 2015.
Reto 4: Consultas de complejidad técnica (Nivel y Categoría). Buscamos material para un seminario avanzado de arquitectura de datos. Necesitamos los títulos de los recursos que pertenezcan a las categorías de "XPath" o "XSLT" y que tengan un nivel de dificultad de 5.
Para la entrega de los 4 retos que os he planteado sobre el catálogo de recursos técnicos, vamos a utilizar GitHub. Ya sabéis que en este módulo no solo aprendemos sintaxis, sino también el flujo de trabajo profesional.

Instrucciones de Entrega en GitHub
Lo importante aquí no es solo que la consulta funcione, sino que el repositorio esté bien organizado. Un "Readme" descuidado es como un código sin comentar: a nadie le gusta leerlo.

1. Estructura del Repositorio. Debéis crear un repositorio público con el nombre LDM-Tarea-XPath-VuestroNombre. Dentro, la estructura debe ser:
/xml/recursos.xml: El archivo de datos de los 30 registros.
/xml/recursos.xsd: El esquema de validación.
consultas_xpath.xbook: El XPath Notebook con las 4 consultas ejecutadas y su resultado. Si preferís no usar el notebook, podéis entregar un consultas.md con los enunciados y las expresiones XPath bien formateadas.
README.md: Una breve explicación de la práctica.
2. Formato del Notebook. En cada celda de vuestro Notebook, incluid:
Markdown: el enunciado del reto.
Code (XPath): la consulta propiamente dicha funcional
