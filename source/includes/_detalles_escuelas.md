# Detalles de Escuela

```json

	{
	    "data": [
	        {
	        	"id": 1,
	            "cct": "14DJN0128O",
	            "turn": "MATUTINO",
	            "email": "olgalilly62@hotmail.com",
	            "telephone": "36080845",
	            "zone": 175,
	            "sector": 2,
	            "level": "PREESCOLAR",
	            "program": "GENERAL",
	            "sustenance": "FEDERALIZADO",
	            "links": {
	                "self": "/api/v0.1/schools/1/details/1",
	                "indicators": "/api/v0.1/schools/1/details/1/indicators",
	                "statistics": "/api/v0.1/schools/1/details/1/statistics",
	                "plans": null,
	                "teachers": "/api/v0.1/schools/1/details/1/teachers",
	                "director": "/api/v0.1/academics/1"
	            }
	        },
	        {
	            "id": 557,
	            "cct": "14DJN1483L",
	            "turn": "VESPERTINO",
	            "email": "m.aeta@hotmail.com",
	            "telephone": "36081429",
	            "zone": 175,
	            "sector": 2,
	            "level": "PREESCOLAR",
	            "program": "GENERAL",
	            "sustenance": "FEDERALIZADO",
	            "links": {
	                "self": "/api/v0.1/schools/1/details/557",
	                "indicators": "/api/v0.1/schools/1/details/557/indicators",
	                "statistics": "/api/v0.1/schools/1/details/557/statistics",
	                "plans": null,
	                "teachers": "/api/v0.1/schools/1/details/557/teachers",
	                "director": "/api/v0.1/academics/582"
	            }
	        }
	    ]
	}

```

 Nombre    | Tipo    | Descripción
---------- | ------- | -----------
 id | number  | Identificador universal para este detalle de escuela
 cct | string | Clave de centro de trabajo
 turn | string | El tipo de [turno](#turno)
 email | nullable string | Correo electrónico de este detalle de escuela
 telephone | nullable string | Telefono de este detalle de escuela 
 zone | number | Zona escolar a la que pertenece el centro de trabajo
 sector | number | Sector al que pertenece el centro de trabajo
 level | string | Nivel educativo que imparte el centro de trabajo
 program | string | programa educativo que imparte el centro de trabajo
 sustenance | number | Fuente de sostenimiento

 ### Turno

 Turnos | Descripción
------- | -----------
 CONTINUO (JORNADA AMPLIADA) | Sin descripción
 CONTINUO (TIEMPO COMPLETO) | Sin descripción
 DISCONTINUO | Sin descripción
 MATUTINO | Sin descripción
 NOCTURNO | Sin descripción
 VESPERTINO | Sin descripción

## Recupera un solo de detalle de una escuela

```json

	{
	    "data": {
	        "id": 1,
	        "cct": "14DJN0128O",
	        "turn": "MATUTINO",
	        "email": "olgalilly62@hotmail.com",
	        "telephone": "36080845",
	        "zone": 175,
	        "sector": 2,
	        "level": "PREESCOLAR",
	        "program": "GENERAL",
	        "sustenance": "FEDERALIZADO",
	        "links": {
	            "self": "/api/v0.1/schools/1/details/1",
	            "indicators": "/api/v0.1/schools/1/details/1/indicators",
	            "statistics": "/api/v0.1/schools/1/details/1/statistics",
	            "plans": null,
	            "teachers": "/api/v0.1/schools/1/details/1/teachers",
	            "director": "/api/v0.1/academics/1"
	        }
	    }
	}

```