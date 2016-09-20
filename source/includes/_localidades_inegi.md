# Localidades Inegi

```json
	
	{
	    "data": [
	        {
	            "id": 1,
	            "name": "GUADALAJARA",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/inegi/locations/1"
	                }
	            ]
	        },
	        ...
	    ],
	    "meta": {
	        "pagination": {
	            "total": 501,
	            "count": 15,
	            "per_page": 15,
	            "current_page": 1,
	            "total_pages": 34,
	            "links": {
	                "next": "/api/v0.1/inegi/locations?page=2"
	            }
	        }
	    }
	}

```

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para esta localidad
 nombre | string | Nombre de la localidad 

## Recuperar una localidad

```json
	
	{
	    "data": {
	        "id": 1,
	        "name": "GUADALAJARA",
	        "links": [
	            {
	                "rel": "self",
	                "href": "/api/v0.1/inegi/locations/1"
	            }
	        ]
	    }
	}

```