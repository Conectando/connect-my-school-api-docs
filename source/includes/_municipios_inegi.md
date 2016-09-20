# Municipios Inegi

```json
	
	{
	    "data": [
	        {
	            "id": 1,
	            "name": "ACATIC",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/inegi/municipalities/1"
	                }
	            ]
	        },
	        ...
	    ],
	    "meta": {
	        "pagination": {
	            "total": 125,
	            "count": 15,
	            "per_page": 15,
	            "current_page": 1,
	            "total_pages": 9,
	            "links": {
	                "next": "/api/v0.1/inegi/municipalities?page=2"
	            }
	        }
	    }
	}
```

 Nombre    | Tipo    | Descripción
---------- | ------- | -------
 id | number | Identificador universal para este municipio
 nombre | string | Nombre del municipio 

## Recuperar un municipio

```json
	
	{
	    "data": {
	        "id": 1,
	        "name": "ACATIC",
	        "links": [
	            {
	                "rel": "self",
	                "href": "/api/v0.1/inegi/municipalities/1"
	            }
	        ]
	    }
	}

```