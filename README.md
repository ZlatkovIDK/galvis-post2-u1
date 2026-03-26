# galvis-post2-u1
Laboratorio 2 - Análisis de peticiones HTTP con Postman.

# Análisis de Peticiones HTTP — Unidad 1
## Descripción
Repositorio de análisis de peticiones HTTP/HTTPS realizado con
Chrome DevTools y Postman como parte del laboratorio 2 de
Programación Web — Séptimo Semestre.
## Herramientas utilizadas
- Google Chrome + DevTools (panel Network)
- Postman (petición POST con tests)
## Análisis realizados
| # | Tipo | URL | Código |
|---|------|-----|--------|
| 1 | GET HTML | https://example.com | 200 OK | [ver análisis](analisis/01-pagina-html.md) 
| 2 | GET JSON (exitoso) | /posts/1 | 200 OK | [ver análisis](analisis/02-api-rest-get.md) 
| 3 | GET JSON (fallido) | /posts/999 | 404 Not Found | [ver análisis](analisis/02-api-rest-get.md) 
| 4 | POST JSON | /posts | 201 Created | [ver análisis](analisis/03-postman-post.md)
## Conclusiones
[En este laboratorio se analizaron diferentes tipos de peticiones HTTP utilizando Chrome DevTools y Postman. Se realizaron peticiones GET a una página HTML y a una API REST, así como una petición POST para crear un nuevo recurso. 
Los análisis revelaron información valiosa sobre los headers de request y response, los códigos de estado devueltos por el servidor, y los tiempos de carga asociados a cada petición. 
En general, se observó que las peticiones GET a la API REST tuvieron tiempos de respuesta más largos que la página HTML, lo cual es común debido a la naturaleza de las APIs. 
Además, se destacó la importancia de monitorear regularmente el rendimiento de los sitios web y APIs para asegurar que se mantengan rápidos y eficientes a medida que se agregan nuevos contenidos o funcionalidades. 
Este ejercicio proporcionó una comprensión más profunda de cómo funcionan las peticiones HTTP y cómo interpretar los datos obtenidos a través de herramientas como DevTools y Postman, lo cual es esencial para el desarrollo web moderno.] 