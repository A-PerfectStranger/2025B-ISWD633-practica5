## Conocimientos Antes de la Práctica
Desconocía la complejidad de orquestar múltiples servicios trabajando en conjunto. No sabía que existían herramientas especializadas para gestionar aplicaciones multi-contenedor.

## Durante la Práctica
Aprendí que Docker Compose simplifica enormemente el despliegue de aplicaciones complejas al permitir definir toda la infraestructura en un solo archivo compose.yaml. 
Descubrí cómo configurar servicios interdependientes, como MySQL y WordPress, donde uno depende del estado saludable del otro mediante la opción _depends_on_ con condition: _service_healthy_.
Comprendí la importancia de las variables de entorno para configurar los servicios sin modificar las imágenes base, y practiqué el mapeo de puertos para exponer servicios al host. También implementé healthchecks específicos para cada tipo de servicio: usando mysqladmin ping para bases de datos y curl para servidores web.
Además, trabajé con políticas de reinicio para garantizar la disponibilidad continua de los servicios, y aprendí a utilizar volúmenes nombrados para persistir datos más allá del ciclo de vida de los contenedores.

## Problemas Encontrados y Soluciones
No hubo problemas significativos al ejecutar la práctica.
