# API v0.1 Introducción

> Estamos trabajando duro en crear un api increible. <br/><br/> [Encuentra el codigo funte aqui...](https://github.com/Conectando/connect-my-school-api-docs).

Bienvenido a la documentación oficial de "Conectando Mi Escuela" <br/> 

## Requests

 Metodo        | Descripción
-------------- | -------
 GET           | Descripción de metodo HTTP GET
 HEAD          | Descripción de metodo HTTP HEAD
 POST          | Descripción de metodo HTTP POST
 DELETE        | Descripción de metodo HTTP DELETE
 PUT           | Descripción de metodo HTTP PUT
 PATCH         | Descripción de metodo HTTP PATCH


## HTTP Status

 Estado        | Descripción
-------------- | -------
 200           | Descripción del estado 200
 201           | Descripción del estado 201
 204           | Descripción del estado 204
 403           | Descripción del estado 403
 404           | Descripción del estado 404
 500           | Descripción del estado 500

## Response

> Response de un unico objeto

```json

	{
		"data": {
			"id": 6567,
			"name": "Cristian Jaramillo"
			...
		}
	}

```

> Response de una collección de objetos

```json

	{
		"data": [
			{
				"id": 6567,
				"name": "Cristian Jaramillo"
				...
			},
			{
				"id": 6787,
				"name": "Mitztli Melgoza"
				...
			}
		]
	}

```

## Meta

> Ejemplo de meta

```json
	
	{
		"meta": {
			"pagination": {
		    	"total": 12324,
		    	"count": 30,
		    	"per_page": 30,
		    	"current_page": 1,
		    	"total_pages": 411,
		    	"links": {
		    		"next": "/api/v0.1/schools?page=2"
		    	}
		    }
		}
	}	

```

 Nombre       | Tipo    | Descripción
--------------| ------- | -------
 total        | number  | sin descripción
 count        | number  | sin descripción
 per_page     | number  | sin descripción
 current_page | number  | sin descripción
 total_pages  | number  | sin descripción


## Links

> Ejemplo de links

```json

	"links": {
    	"self": "/api/v0.1/schools/1",
    	"details": "/api/v0.1/schools/1/details",
    	"location": "/api/v0.1/inegi/locations/1",
    	"municipality": "/api/v0.1/inegi/municipalities/39"
    }

```

## Rate Limit

> Ejemplo de RateLimit Headers

```

	X-RateLimit-Limit: 60
	X-RateLimit-Remaining: 58
	X-RateLimit-Reset: 678672

``` 

> Ejemplo de respuesta al superar RateLimit

```

	Too Many Requests

```

## Ejemplo Curl

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

## Cross Origin Resource Sharing

CORS introduce un mecanismo estándar que pueda ser utilizado por todos los navegadores para la implementación de las solicitudes entre dominios. La especificación define un conjunto de cabeceras que permiten la comunicación entre el navegador y el servidor sobre las solicitudes que son y no son permitidas. CORS sigue el espíritu de la web abierta trayendo acceso a la API para todos.
