# Programas Educativos

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para este programa educativo
 nombre | string | Nombre del programa educativo

## Lista todos los programas educativos

```json
	
	{
	    "data": [
	        {
	            "id": 1,
	            "name": "GENERAL",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/educational/programs/1"
	                }
	            ]
	        },
			...
	    ],
	    "meta": {
	        "pagination": {
	            "total": 10,
	            "count": 10,
	            "per_page": 15,
	            "current_page": 1,
	            "total_pages": 1,
	            "links": []
	        }
	    }
	}

```

## Recuperar un programa educativo

```json
	
	{
	    "data": {
	        "id": 1,
	        "name": "GENERAL",
	        "links": [
	            {
	                "rel": "self",
	                "href": "/api/v0.1/educational/programs/1"
	            }
	        ]
	    }
	}

```