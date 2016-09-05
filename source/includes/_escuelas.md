# Escuelas

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para esta escuela
 name | string | Nombre del centro de trabajo
 address | string | Dirección del centro de trabajo
 colony | string | Colonia en la que se encuentra el centro de trabajo
 postal_code | nullable number | Código postal 
 latitude | double | Latitud donde se encuentra el centro de trabajo
 longitude | double | Longitud donde se encuentra el centro de trabajo

## Lista todas las escuelas

```json

	{
	    "data": [
	        {
	            "id": 1,
	            "name": "JUAN DE LA BARRERA",
	            "address": "ARQUIMEDES 723",
	            "colony": "HERMOSA PROVINCIA",
	            "postal_code": 44770,
	            "latitude": 20.6708361,
	            "longitude": -103.2864634,
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/schools/1"
	                },
	                {
	                    "rel": "details",
	                    "href": "/api/v0.1/schools/1/details"
	                }
	            ]
	        },
	        ...
	    ],
	    "meta": {
	        "pagination": {
	            "total": 10334,
	            "count": 15,
	            "per_page": 15,
	            "current_page": 1,
	            "total_pages": 689,
	            "links": {
	                "next": "/api/v0.1/schools?page=2"
	            }
	        }
	    }
	}

```

## Recupera una escuela

```json

	{
	    "data": {
	        "id": 1,
	        "name": "JUAN DE LA BARRERA",
	        "address": "ARQUIMEDES 723",
	        "colony": "HERMOSA PROVINCIA",
	        "postal_code": 44770,
	        "latitude": 20.6708361,
	        "longitude": -103.2864634,
	        "links": [
	            {
	                "rel": "self",
	                "href": "/api/v0.1/schools/1"
	            },
	            {
	                "rel": "details",
	                "href": "/api/v0.1/schools/1/details"
	            }
	        ]
	    }
	}

```