## INFDES 

### tasa_informalidad_productive_legal_ultimo_anio_latam.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio | entero | Año de referencia |
| tipo_informalidad | alfanumerico | Tipo de informalidad de referencia: "Informalidad (definición legal)" o "Informalidad (definición productiva)" |
| valor | real | Participación de trabajadores en el sector informal |


### tasa_formalidad_productiva_pib_per_capita.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| pib_per_capita | real | PIB per cápita basado en la paridad del poder adquisitivo (PPP), a precios constantes de 2017, en dólares internacionales |
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio | entero | Año de referencia |
| tasa_formalidad_productiva | real | Porcentaje de los empleados que son formales (definición productiva) |


### composicion_empleo_ultimo_anio_latam.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio | entero | Año de referencia |
| cat_ocup_detalle | alfanumerico | Categoría ocupacional de referencia |
| cat_ocup_cod | real | Código de categoría ocupacional (es nulo si cat_ocup_detalle es "Total formal") |
| formal_def_productiva | entero | Condicion de formalidad según definición productiva: "formales" o "informales". Es nulo cuando cat_ocup_detalle == "Total formal" |
| valor | real | Participación de trabajadores formales |
 | valor | real | Participación en el total de trabajadores |


### tasa_informalidad_argentina_tipo_anio.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| tipo_informalidad | alfanumerico | Tipo de informalidad de referencia: "Definición legal" o "Definición productiva" |
| valor | real | Participación de trabajadores en el sector informal |


### tasa_informalidad_legal_latam.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio | entero | Año de referencia |
| serie | alfanumerico | Referencia al tipo de serie "Serie original" o "Serie empalmada" |
| valor | real | Participación de trabajadores en el sector informal |


### tasa_informalidad_provincia_definicion_productiva_legal.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| prov_cod | entero | Código de provincia (según INDEC) |
| prov_desc | alfanumerico | Provincia de referencia |
| tipo_informalidad | alfanumerico | Tipo de informalidad de referencia: "Informalidad (definición legal)" o "Informalidad (definición productiva)" |
| valor | real | Participación de trabajadores en el sector informal |


### tasa_informalidad_legal_por_edad_sexo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| edad | entero | Edad de referencia |
| apertura_sexo | alfanumerico | Tipo de apertura por sexo (total, masculino o femenino) |
| tasa_informalidad_legal | real | Porcentaje de los empleados que son informales (definición legal) |


### tasa_informalidad_argentina_genero.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| apertura_sexo | alfanumerico | Tipo de apertura por sexo (varón, mujer, brecha) |
| valor | real | Tasa de informalidad |


### brecha_tasa_informalidad_genero_latam_2000_2021.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio_circa | entero | Año de referencia |
| circa | alfanumerico | Circa de referencia |
| brecha | real | Brecha entre tasa de informalidad femenina y la tasa de informalidad masculina, en puntos porcentuales |


### anios_educacion_genero_por_pais.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais | alfanumerico | País de referencia |
| anio | entero | Año de referencia |
| apertura_sexo | alfanumerico | Tipo de apertura por sexo (varón, mujer) |
| valor | real | Cantidad de años promedio de estudio |


### tasa_desempleo_arg_mundial_modelada.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumérico | Código de país o región de países |
| pais_desc | alfanumérico | País o Región de referencia |
| anio | entero | Año de referencia |
| tasa_desempleo | real | Tasa de desempleo |


### tasa_desempleo_sexo_paises_modelada.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumérico | Código de país o región de países |
| pais_desc | alfanumérico | País o Región de referencia |
| continente_fundar | alfanumérico | Continente de referencia |
| anio | entero | Año de referencia |
| sexo | alfanumérico | Sexo de referencia (Masculino, Femenino, Total) |
| tasa_desempleo | real | Tasa de desempleo |


### satisfaccion_vida_desempleo_pais.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumérico | Código de país o región de países |
| pais_desc | alfanumérico | País o Región de referencia |
| anio | entero | Año de referencia |
| estado | alfanumérico | Estado ocupación ("Ocupado" o "Desocupado") |
| satisfaccion_vida | real | Promedio del nivel de satisfacción con la vida (valores en la escala de 0 a 10) |


### tasa_desempleo_ephtu_sexo_edad.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| rango_edad | entero | Rango de edad (valor ordinal) |
| rango_edad_desc | alfanumérico | Rango de edad (descripción) |
| sexo | alfanumérico | Sexo de referencia (Mujeres, Varones) |
| tasa_desocupacion | real | Tasa de desocupación |


### tasa_desempleo_eph_niveled.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| nivel_ed_cod | entero | Nivel educativo (valor ordinal) |
| nivel_ed_desc | alfanumérico | Nivel educativo (descripción) |
| tasa_desocupacion | real | Tasa de desocupación |


