# Académicos

Son los registros de los académicos que funge como directores y/ó maestros de los centros de trabajo.

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para este académico
 rfc | string (alphanumeric) | El Registro Federal de Contribuyentes (RFC) es una clave alfanumérica compuesta por 13 caracteres (para Personas Físicas) y es utilizada cuando un individuo ejerce actividades económicas por las cuales esté obligado a pagar impuestos.
 name | string | Nombre del académico
 last_name | nullable string | Apellido paterno del académico
 second_last_name | nullable string | Apellido materno del académico
 email | nullable string | Correo electronico del académico
 telephone | nullable string | Teléfono local del académico en formato internacional
 mobile_phone | nullable string | Teléfono celular del académico en formato internacional

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
	Cache-Control: no-cache

```

> Response Body

 ```json

	{
	    "data": [
	        {
	            "id": 1,
	            "rfc": "4947768972322",
	            "name": "OLGA LILIA GARCIA LOPEZ",
	            "last_name": "",
	            "second_last_name": "",
	            "email": "senger.harley@fisher.com",
	            "telephone": "+555607305330",
	            "mobile_phone": "+7941435492013",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/academics/1"
	                }
	            ]
	        },
	        ...
	    ],
	    "meta": {
	        "pagination": {
	            "total": 10520,
	            "count": 15,
	            "per_page": 15,
	            "current_page": 1,
	            "total_pages": 702,
	            "links": {
	                "next": "/api/v0.1/academics?page=2"
	            }
	        }
	    }
	}

```

## Recuperar un académico

```json

	{
	    "data": {
	        "id": 15,
	        "rfc": "3476063976762",
	        "name": "EVANGELINA ANGEL GARCIA",
	        "last_name": "",
	        "second_last_name": "",
	        "email": "aleen.koch@hotmail.com",
	        "telephone": "+081406626455",
	        "mobile_phone": "+0801413950168",
	        "links": [
	            {
	                "rel": "self",
	                "href": "/api/v0.1/academics/15"
	            }
	        ]
	    }
	}

```