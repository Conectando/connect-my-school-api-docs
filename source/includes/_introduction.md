# API v0.1 Introducción

> Estamos trabajando duro en crear un api increible. <br/><br/> [Encuentra el codigo funte aqui...](https://github.com/Conectando/connect-my-school-api-docs).

Bienvenido a la documentación oficial de "Conectando Mi Escuela" <br/> 

## Cross Origin Resource Sharing

CORS introduce un mecanismo estándar que pueda ser utilizado por todos los navegadores para la implementación de las solicitudes entre dominios. La especificación define un conjunto de cabeceras que permiten la comunicación entre el navegador y el servidor sobre las solicitudes que son y no son permitidas. CORS sigue el espíritu de la web abierta trayendo acceso a la API para todos.

```cURL

	curl -I -H "Accept: aplication/json" -GET "http://api.school.dev/v0.1/schools"

```

> Request Headers

```curl

	HEAD /v0.1/schools HTTP/1.1
	Host: api.school.dev
	User-Agent: curl/7.46.0
	Accept: aplication/json

```

> Response Headers

```curl

	HTTP/1.1 200 OK
	Host: api.school.dev
	Connection: close
	X-Powered-By: PHP/7.0.9
	Cache-Control: no-cache
	Content-Type: application/json
	X-RateLimit-Limit: 60
	X-RateLimit-Remaining: 58
	Date: Mon, 29 Aug 2016 19:33:15 GMT

```