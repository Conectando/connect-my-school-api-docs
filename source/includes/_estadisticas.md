# Estadisticas

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

 Nombre     | Tipo   | Descripción
----------- | ------ | ------------
students    | object | Información de estudiantes 
employees   | object | Información de empleados
groups      | number | Total de grupos

## students (objetc)

 Nombre     | Tipo   | Descripción
----------- | ------ | ------------
first       | object | Información de alumnos en primer grado/semestre
second      | object | Información de alumnos en segundo grado/semestre
third       | object | Información de alumnos en tercer grado/semestre
fourth      | object | Información de alumnos en cuarto grado/semestre
fifth       | object | Información de alumnos en quinto grado/semestre
sixth       | object | Información de alumnos en sexto grado/semestre
total_men   | number | Total de alumnos hombres en todos los grados ó semestres 
total_women | number | Total de alumnas mujeres en todos los grados ó semestres
total       | number | Total de alumnos de todos los grados ó semestres

### first, second, third, fourth, fifth, sixth

 Nombre    | Tipo   | Descripción
---------- | ------ | ------------
 mens      | number | Total de alumnos hombres de este grado/semestre
 women     | number | Total de alumnas mujeres de este grado/semestre
 total     | number | Total de alumnos de todo el grado/semestre

## employees (objetc)

 Nombre         | Tipo   | Descripción
--------------- | ------ | ------------
 teachers       | object | Información de profesores 
 administrative | number | Total de empleados adminisrativos
 total          | number | Total de empleados

### teachers (object)

 Nombre                   | Tipo   | Descripción
------------------------- | ------ | ------------------------------
 general                  | number | Total de profesores generales
 physical_education       | number | Total de profesores de educación fisica
 artistic_activities      | number | Total de profesores de actividades artisticas
 technological_activities | number | Total de profesores de actividades tecnologicas
 language                 | number | Total de profesores de idiomas
