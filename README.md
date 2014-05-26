opentoken-ws
============

Webservices de interacción con OpenToken (https://github.com/Tok3n/OpenTok3n) proyecto basado en Go para la gestión de autentificación basado en llaves privadas y públicas.

El proyecto interactuara usando webservices que sea posible hacer las siguientes tareas:
 * Generar llaves privadas y públicas
 * Consumirlas y procesarlas como JSON usando el metodo GET
 * Validar algun mensaje junto con su firma

El proyecto esta basado en proveer una solución de backend para la interacción con el proyecto de OpenToken.

Se usara el net/http para generar las llamaddas a OpenToken para las llaves necesarias. Estas llaves se generaran a partir de la librería criptográfica ed25519 dentro de OpenToken usando las instrucciones:
 * 
