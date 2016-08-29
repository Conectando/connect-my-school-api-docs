# Detalles de Escuelas

```json
[
	{
	    "id": 1,
	    "escuela_id": 1,
	    "clave_ct": "14DJN0128O",
	    "nivel_id": 1,
	    "academico_id": 1,
	    "programa_id": 1,
	    "turno": "MATUTINO",
	    "correo": "olgalilly62@hotmail.com",
	    "telefono": "36080845",
	    "zona": 175,
	    "sector": 2,
	    "sotenimiento": "FEDERALIZADO",
	    "created_at": "2016-08-28 06:50:02",
	    "updated_at": "2016-08-28 06:50:02"
	},
]
```

 Nombre    | Tipo    | Descripción
---------- | ------- | -----------
 id | number  | Identificador universal para este detalle de escuela
 escuela_id | number | Identificador universal que hace referencia a una [escuela](#escuelas)
 clave_ct | string | Clave de centro de trabajo
 nivel_id | number | Identificador universal que hace referencia a un [nivel](#niveles)
 academico_id | nullable number | Identificador universal que hace referencia a un [academico](#academicos) 
 programa_id | number | Identificador universal que hace referencia a un [programa](#programas) 
 turno | string | El tipo de [turno](#turno)
 correo | nullable string | Correo electrónico de este detalle de escuela
 telefono | nullable string | Telefono de este detalle de escuela 
 zona | number | Zona escolar a la que pertenece el centro de trabajo
 sector | number | Sector al que pertenece el centro de trabajo
 sostenimiento | number | Fuente de sostenimiento
 created_at | timestamp | Fecha de creación del registro
 updated_at | timestamp | Fecha de ultima actualización del registro

 ## Turno

 Turnos | Descripción
------- | -----------
 CONTINUO (JORNADA AMPLIADA) | Sin descripción
 CONTINUO (TIEMPO COMPLETO) | Sin descripción
 DISCONTINUO | Sin descripción
 MATUTINO | Sin descripción
 NOCTURNO | Sin descripción
 VESPERTINO | Sin descripción
