# Indicadores

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

 Nombre     | Tipo   | Descripción
----------- | ------ | ------------
desercion   | double | Porsentaje de deserción
reprobacion | object | Porsentajes de reprobación
eficiencia  | double | Porsentaje de eficiencia

## reprobacion (object)

 Nombre         | Tipo   | Descripción
--------------- | ------ | ------------
 ordinaria      | double | Porsentaje alumnos reprobados en periodo ordinario
 regularizados  | double | Porsentaje alumnos reprobados tras una regularización