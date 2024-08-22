## MERTRA 

### tasa_participacion_censos.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sexo | alfanumérico | Apertura por sexo (Ambos, Mujeres, Varones) |
| tasa_participacion | real | Porcentaje que representa la población económicamente activa (PEA) respecto a la de 14 y más años de edad |


### ratio_tasa_actividad_mujer_varon_por_pais_anio.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ratio_tasa_actividad_mujer_varon | real | Ratio entre la tasa de actividad de mujeres y la tasa de actividad de varones, por país y año |
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc | alfanumerico | Nombre de país o región de paises |
| nivel_agregacion | entero | Identificador de país: 0 o region de paises: 1 |
| anio | entero | Año de referencia |


### tasa_actividad_por_pais_anio.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tasa_actividad | real | Ratio entre la cantidad de personas pertenecientes a la población económicamente activa y la población total |
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |
| iso3_desc | alfanumerico | Nombre de país o región de paises |
| nivel_agregacion | entero | Identificador de país: 0 o region de paises: 1 |


### media_movil_por_edad_de_tasa_actividad.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tasa_actividad | real | Ratio entre la cantidad de personas pertenecientes a la población económicamente activa y la población total, por grupo etario (media movil cada 5 años de edad). |
| edad | entero | Edad de referencia |
| anio | entero | Año de referencia |


### media_movil_por_edad_sexo_de_tasa_actividad_brecha.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| edad | entero | Edad de referencia |
| apertura_sexo | alfanumerico | Tipo de apertura por género (Total, Varón, Mujer o Brecha) |
| valor | real | Media móvil por quinquenios etarios de la tasa de actividad |


### media_movil_por_edad_reg_desc_fundar_de_tasa_actividad.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| edad | entero | Edad de referencia |
| reg_desc_fundar | alfanumerico | Región de referencia (elaboración Fundar en base a regiones EPHTU-INDEC) |
| tasa_actividad | real | Media móvil por quinquenios etarios de la tasa de actividad |


### puestos_percapita_anio_pais.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| puestos_per_capita | real | Cantidad de puestos de trabajo sobre el total de la poblacion |
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |


### tasa_empleo_anio_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| provincia | alfanumerico | Provincia de referencia (incluye Total) |
| tasa_empleo | real | Ratio entre la cantidad de personas ocupadas y la cantidad de personas pertenecientes a la población económicamente activa |


### tasa_empleo_por_franja_etaria_anio_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| prov_desc | alfanumerico | Provincia de referencia (incluye Total) |
| apertura_edad | alfanumerico | Tipo de apertura por edad: "Edad, menor a 18", "Edad, 18 a 65", "Edad, mayor a 65" y "Edad, Total" |
| tasa_empleo | real | Ratio entre la cantidad de personas ocupadas y la cantidad de personas pertenecientes a la población económicamente activa |


### tasa_empleo_anio_provincia_sexo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| provincia | alfanumerico | Provincia de referencia (incluye Total) |
| sexo | alfanumerico | Tipo de apertura por género (Total, Varón o Mujer) |
| tasa_empleo | real | Ratio entre la cantidad de personas ocupadas y la cantidad de personas pertenecientes a la población económicamente activa |


### tasa_empleo_menores_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| provincia | alfanumerico | Provincia de referencia |
| tasa_empleo | real | Ratio entre la cantidad de personas ocupadas y la cantidad de personas pertenecientes a la población económicamente activa |
| tasa_menor_18 | real | Participación de personas menores a 18 años de edad en la población |


### establecimientos_tasa_empleo_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| establecimientos_cada_1000_hab | real | Cantidad de establecimientos de trabajo en 2021 cada 1000 habitantes, según la población de 2022 |
| tasa_empleo_18_65 | real | Ratio entre la cantidad de personas ocupadas entre 18 y 65 años y la cantidad de personas pertenecientes a la población económicamente activa entre 18 y 65 años |
| provincia_id | entero | Código único de provincia, según INDEC |
| provincia_desc | alfanumerico | Provincia de referencia (incluye Total) |


### tasa_empleo_mujer_salario_provincia_anio.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| provincia | alfanumérico | Provincia de referencia |
| anio | entero | Año de referencia |
| salario_relativo | real | Proporción del salario relativo al salario máximo nacional |
| tasa_empleo_mujer | real | Proporción de la población de mujeres entre 18 y 65 años que se encuentra empleada |


### lavarropas_tasa_empleo_fem_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| prov_desc | alfanumerico | Provincia de referencia (incluye Total) |
| prop_usa_lavarropas | real | Participación de hogares con lavarropas automáticos |
| prov_cod | entero | Código único de provincia, según INDEC |
| tasa_empleo_18_65_mujeres | real | Ratio entre la cantidad de personas sexo femenino ocupadas entre 18 y 65 años y la cantidad de personas sexo femenino entre 18 y 65 años pertenecientes a la población económicamente activa |


### share_acuerdo_varones_empleo_region_arg.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| region_wvs_code | entero | Código regiones según World Values Survey |
| region_wvs | alfanumerico | Región argentina segíun World Values Survey |
| nivel_acuerdo | alfanumerico | Nivel de acuerdo o desacuerdo con respecto a la frase: "Cuando escasean los empleos, los varones deberían tener mayor derecho a trabajar que las mujeres" |
| valor | real | Participación del nivel de acuerdo en el total de encuestados |


### tasa_empleo_provincia_nivel_educativo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| provincia | alfanumerico | Provincia de referencia |
| nivel_ed_fundar | alfanumérico | Nivel educativo de referencia |
| ocupado | real | Ratio entre la cantidad de personas ocupadas y la cantidad de personas pertenecientes a la población económicamente activa |


### tiempo_social_trabajo_sexo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tipo_trabajo | alfanumérico | Tipo de trabajo ("En la ocupación", "No remunerado", "total") |
| sexo | alfanumérico | Sexo de referencia (Mujeres, Varones y Total) |
| minutos | entero | Promedio de minutos diarios dedicados al trabajo |


### tiempo_social_trabajo_sexo_edad.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sexo | alfanumérico | Sexo de referencia (Mujeres, Varones y Total) |
| grupo_edad | alfanumérico | Grupo de Edad |
| minutos | real | Promedio de minutos diarios dedicados al trabajo |


### tiempo_social_trabajo_sexo_niveleducativo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sexo | alfanumérico | Sexo de referencia (Mujeres, Varones y Total) |
| nivel_educativo | alfanumérico | Nivel Educativo |
| minutos | real | Promedio de minutos diarios dedicados al trabajo |


### tipo_trabajo_no_rem_sexo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tipo_trabajo | alfanumérico | Tipo de trabajo ("Apoyo a otros hogares, para la comunidad y voluntario", "Cuidados a otros miembros del hogar", "Doméstico") |
| sexo | alfanumérico | Sexo de referencia (Mujeres, Varones y Total) |
| minutos | real | Promedio de minutos diarios dedicados |


### trabajo_no_remunerado_sexo_internacional.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumérico | Código de país o región de países |
| pais_desc | alfanumérico | País o Región de referencia |
| continente_fundar | alfanumérico | Continente de referencia |
| anios_observados | alfanumérico | Ultimo período de años observados disponibles |
| share_trabajo_no_remun | entero | Promedio de minutos diarios dedicados |


