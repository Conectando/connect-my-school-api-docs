# Académicos

Son los registros de los académicos que funge como directores y/ó maestros de los centros de trabajo.

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para este académico
 rfc | string (alphanumeric) | El Registro Federal de Contribuyentes (RFC) es una clave alfanumérica compuesta por 13 caracteres (para Personas Físicas) y es utilizada cuando un individuo ejerce actividades económicas por las cuales esté obligado a pagar impuestos.
 nombre | string | Nombre del académico
 apaterno | nullable string | Apellido paterno del académico
 amaterno | nullable string | Apellido materno del académico
 telefono | nullable string | Teléfono local del académico en formato internacional
 celular | nullable string | Teléfono celular del académico en formato internacional
 correo | nullable string | Correo electronico del académico
 created_at | timestamp | Fecha de creación del registro
 updated_at | timestamp | Fecha de ultima actualización del registro

## Lista de todos los académicos

> Ejemplo

```cURL

	curl -X GET "http://api.school.dev/v0.1/schools" 

```

```CSharp

	var client = new RestClient("http://api.school.dev/v0.1/schools");
	var request = new RestRequest(Method.GET);
	request.AddHeader("Accept", "application/json");
	IRestResponse response = client.Execute(request);

```

```Java
	
	OkHttpClient client = new OkHttpClient();

	Request request = new Request.Builder()
		.url("http://api.school.dev/v0.1/schools")
		.get()
		.addHeader("Accept", "application/json")
		.build();

	Response response = client.newCall(request).execute();

```

```Javascript

	var settings = {
		"async": true,
		"crossDomain": true,
		"url": "http://api.school.dev/v0.1/schools",
		"method": "GET",
		"headers": {
			"Accept": "application/json"
		}
	}

	$.ajax(settings).done(function (response) {
	  console.log(response);
	});

```

```PHP

	<?php

		$request = new HttpRequest();
		$request->setUrl('http://api.school.dev/v0.1/schools');
		$request->setMethod(HTTP_METH_GET);

		$request->setHeaders(array(
		  'Accept'-> 'application/json'
		));

		try {
		  $response = $request->send();

		  echo $response->getBody();
		} catch (HttpException $ex) {
		  echo $ex;
		}

```

> Request Headers

```

	Accept: application/json

```

> Response Headers

```

	Content-Type: application/json
	Date: Sun, 28 Aug 2016 22:10:52 GMT
	Host: api.school.dev
	X-Powered-By: nginx
	X-RateLimit-Limit: 60
	X-RateLimit-Remaining: 59

```

> Response Body

 ```json

	[
		{
			"id": 1,
			"rfc": "0780903581928",
		    "nombre": "OLGA LILIA",
		    "apaterno": "GARCIA",
		    "amaterno": "LOPEZ",
		    "telefono": "+962500819124",
		    "celular": "+4434633253867",
		    "correo": "queenie71@rempel.com",
		    "created_at": "2016-08-28 06:36:45",
		    "updated_at": "2016-08-28 06:36:45"
		},
		...
	]

```
