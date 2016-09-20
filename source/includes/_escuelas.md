# Escuelas

```json

	{
	    "data": [
	        {
	            "id": 1,
	            "name": "JUAN DE LA BARRERA",
	            "address": "ARQUIMEDES 723",
	            "colony": "HERMOSA PROVINCIA",
	            "postal_code": 44770,
	            "location": "GUADALAJARA",
	            "municipality": "GUADALAJARA",
	            "state": "JALISCO",
	            "latitude": 20.6708361,
	            "longitude": -103.2864634,
	            "links": {
	                "self": "/api/v0.1/schools/1",
	                "details": "/api/v0.1/schools/1/details",
	                "location": "/api/v0.1/inegi/locations/1",
	                "municipality": "/api/v0.1/inegi/municipalities/39"
	            }
	        },
	        ...
	    ],
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

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para esta escuela
 name | string | Nombre del centro de trabajo
 address | string | Dirección del centro de trabajo
 colony | string | Colonia en la que se encuentra el centro de trabajo
 postal_code | nullable number | Código postal 
 latitude | double | Latitud donde se encuentra el centro de trabajo
 longitude | double | Longitud donde se encuentra el centro de trabajo

## Recupera una escuela

```json

	{
		"data": {
		    "id": 1,
		    "name": "JUAN DE LA BARRERA",
		    "address": "ARQUIMEDES 723",
		    "colony": "HERMOSA PROVINCIA",
		    "postal_code": 44770,
		    "location": "GUADALAJARA",
		    "municipality": "GUADALAJARA",
		    "state": "JALISCO",
		    "latitude": 20.6708361,
		    "longitude": -103.2864634,
		    "links": {
		      "self": "/api/v0.1/schools/1",
		      "details": "/api/v0.1/schools/1/details",
		      "location": "/api/v0.1/inegi/locations/1",
		      "municipality": "/api/v0.1/inegi/municipalities/39"
		    }
		}
	}

```