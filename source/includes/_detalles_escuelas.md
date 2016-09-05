# Detalles de Escuela

 Nombre    | Tipo    | Descripción
---------- | ------- | -----------
 id | number  | Identificador universal para este detalle de escuela
 key | string | Clave de centro de trabajo
 turn | string | El tipo de [turno](#turno)
 email | nullable string | Correo electrónico de este detalle de escuela
 telephone | nullable string | Telefono de este detalle de escuela 
 zone | number | Zona escolar a la que pertenece el centro de trabajo
 sector | number | Sector al que pertenece el centro de trabajo
 sustenance | number | Fuente de sostenimiento

 ## Turno

 Turnos | Descripción
------- | -----------
 CONTINUO (JORNADA AMPLIADA) | Sin descripción
 CONTINUO (TIEMPO COMPLETO) | Sin descripción
 DISCONTINUO | Sin descripción
 MATUTINO | Sin descripción
 NOCTURNO | Sin descripción
 VESPERTINO | Sin descripción

## Lista todos los detalles de una escuela

```json

	{
	    "data": [
	        {
	            "id": 1,
	            "key": "14DJN0128O",
	            "turn": "MATUTINO",
	            "email": "olgalilly62@hotmail.com",
	            "telephone": "36080845",
	            "zone": 175,
	            "sector": 2,
	            "sustenance": "FEDERALIZADO",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/schools/1/details/1"
	                },
	                {
	                    "rel": "indicators",
	                    "href": "/api/v0.1/schools/1/details/1/indicators"
	                },
	                {
	                    "rel": "statistics",
	                    "href": "/api/v0.1/schools/1/details/1/statistics"
	                },
	                {
	                    "rel": "teachers",
	                    "href": "/api/v0.1/schools/1/details/1/teachers"
	                }
	            ]
	        },
	        ...
	    ]
	}

```

## Recupera un detalle de una escuela

```json

	{
	    "data": [
	        {
	            "id": 1,
	            "key": "14DJN0128O",
	            "turn": "MATUTINO",
	            "email": "olgalilly62@hotmail.com",
	            "telephone": "36080845",
	            "zone": 175,
	            "sector": 2,
	            "sustenance": "FEDERALIZADO",
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/schools/1/details/1"
	                },
	                {
	                    "rel": "indicators",
	                    "href": "/api/v0.1/schools/1/details/1/indicators"
	                },
	                {
	                    "rel": "statistics",
	                    "href": "/api/v0.1/schools/1/details/1/statistics"
	                },
	                {
	                    "rel": "teachers",
	                    "href": "/api/v0.1/schools/1/details/1/teachers"
	                }
	            ]
	        }
	    ]
	}

```