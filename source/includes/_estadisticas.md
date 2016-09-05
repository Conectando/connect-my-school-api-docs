# Estadisticas

 Nombre     | Tipo   | Descripción
----------- | ------ | ------------
students    | object | Información de estudiantes 
employees   | object | Información de empleados
groups      | number | Total de grupos

## Recupera una estadistica

```json

	{
	    "data": [
	        {
	            "students": {
	                "first": {
	                    "mens": 0,
	                    "women": 0,
	                    "tatal": 0
	                },
	                "second": {
	                    "mens": 42,
	                    "women": 53,
	                    "tatal": 95
	                },
	                "third": {
	                    "mens": 50,
	                    "women": 47,
	                    "tatal": 97
	                },
	                "fourth": {
	                    "mens": 0,
	                    "women": 0,
	                    "tatal": 0
	                },
	                "fifth": {
	                    "mens": 0,
	                    "women": 0,
	                    "tatal": 0
	                },
	                "sixth": {
	                    "mens": 0,
	                    "women": 0,
	                    "tatal": 0
	                },
	                "total_men": 0,
	                "total_women": 0,
	                "total": 192
	            },
	            "employees": {
	                "teachers": {
	                    "general": 6,
	                    "physical_education": 1,
	                    "artistic_activities": 1,
	                    "technological_activities": 0,
	                    "language": 0
	                },
	                "administrative": 2,
	                "total": 11
	            },
	            "groups": 6,
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/schools/1/details/1/statistics"
	                }
	            ]
	        }
	    ]
	}

```