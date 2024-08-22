## DESHUM 

### indice_desarrollo_humano.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | entero | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| idh | real | Índice de Desarrollo Humano (IDH) |


### expectativa_vida.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | entero | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| expectativa_vida | real | Expectativa de vida al nacer, en años |


### inb_pc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | alfanumerico | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| inb_pc | real | Ingreso Nacional Bruto (INB) per cápita, en dólares PPP de 2017 |


### anios_prom_educ.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | entero | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| anios_prom_educ | real | Años promedio de educación de la pblación de 25 años o más |


### expectativa_educ.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | entero | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| expectativa_educ | real | Años de educación esperados |


### idh_subcomponentes.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| country | alfanumerico | Descripción de país o región de países |
| anio | entero | Año al que corresponden los datos |
| idh_tipo | alfanumerico | Variable que da cuenta a qué IDH corresponde valor |
| valor | real | Valor del IDH que corresponda, según idh_tipo |


### idh_idhd.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año al que corresponden los datos |
| country | alfanumerico | Descripción de país o región de países |
| idh | real | Índice de Desarrollo Humano (IDH) |
| idh_d | real | Índice de Desarrollo Humano ájustado por desigualdad |


### indice_desarrollo_humano_desigualdad.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | alfanumerico | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| idhd | real | Índice de Desarrollo Humano (IDH) ajustado por desigualdad |


### gdi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año al que corresponden los datos |
| country | alfanumerico | Descripción de país o región de países |
| gdi | real | Índice de Desarrollo de Género |


### idh_sexo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| country | alfanumerico | Descripción de país o región de países |
| anio | entero | Año al que corresponden los datos |
| sexo | alfanumerico | Sexo al nacer |
| idh | real | Índice de Desarrollo Humano (IDH) |


### idh_dif_idhp.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| pais_nombre | alfanumerico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente |
| es_agregacion | entero | Variable que identifica el nivel de agregación de la entidad geográfica ('pais' o 'agregacion') |
| anio | entero | Año al que corresponden los datos |
| idh | real | Índice de Desarrollo Humano (IDH) |
| dif_idh_idhp | real | Pérdida de IDH al ajustar por presiones planetarias (en porcentaje) |


### ranking_diferencia_idh_idhp_2022_flourish.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| tipo_idh | alfanumerico | Variable que da cuenta a qué IDH corresponde valor |
| country | alfanumerico | Descripción de país o región de países |
| ranking_2022 | entero | Ubicación en el ranking de IDH o IDH-P, segun corresponda |


### idh_idhp.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año al que corresponden los datos |
| tipo_idh | alfanumerico | Variable que da cuenta a qué IDH corresponde valor |
| country | alfanumerico | Descripción de país o región de países |
| valor | real | Valor del IDH que corresponda, según tipo_idh |


### idha_subindices.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Descripción de país o región de países |
| anio | entero | Año al que corresponden los datos |
| idha_subdimension | alfanumerico | Variable que da cuenta a qué subdimensión del IDH-A corresponde valor |
| valor | real | Valor del IDH que corresponda, según tipo_idh |


### idha.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Descripción de país o región de países |
| anio | entero | Año al que corresponden los datos |
| idha | real | Variable que da cuenta a qué subdimensión del IDH-A corresponde valor |


