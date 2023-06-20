# API_REST
Proyecto que contiene la API creada con PHP y es consumida a través de un html, en el que se desarrolla un entorno de alumno-asignatura-descripción.

Para procesar las peticiones considerando el CORS, recurrimos al archivo httpd de APACHE para agregar lo siguiente:
#MODULO PARA HABILITAR CORS EN APACHE
<IfModule mod_headers.c>
  Header add Access-Control-Allow-Origin "*"
    Header add Access-Control-Allow-Methods "GET,POST,PUT,DELETE,OPTIONS"
    Header add Access-Control-Allow-Headers "Content-Type,Authorization,X-Requested-With"
    Header add Access-Control-Allow-Credentials "true"
</IfModule>

