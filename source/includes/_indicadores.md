# Indicadores

 Nombre     | Tipo   | Descripción
----------- | ------ | ------------
desercion   | double | Porsentaje de deserción
reprobacion | object | Porsentajes de reprobación
eficiencia  | double | Porsentaje de eficiencia

## Recupera un indicador

```json

	{
	    "data": [
	        {
	            "desercion": 0,
	            "reprobacion": {
	                "ordinaria": 0,
	                "regularizados": 0
	            },
	            "eficiencia": 0,
	            "links": [
	                {
	                    "rel": "self",
	                    "href": "/api/v0.1/schools/1/details/1/indicators"
	                }
	            ]
	        }
	    ]
	}

```