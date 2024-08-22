## ESTPRO 

### particip_sector_vab.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (INDEC), letra. |
 | letra | entero | Agregación sectorial a nivel de letra (letra) |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (INDEC), descripción abreviada. |
 | letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (descripción) |
| id_tipo_sector | entero | Indica si los sectores productivos son bienes o servicios (código). |
| tipo_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |
| particip_vab | real | Participación sectorial en el Valor Agregado Bruto Nacional, por parte de cada sector productivo. Para Argentina. |
 | particip_vab | real | Participación del VAB por sector productivo (a nivel de letra) |


### vab_por_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra_desc | alfanumerico | Codificación del sector económico |
| vab | real | Valor Agregado Bruto, en millones de pesos de 2004 |
| letra | alfanumerico | Descripción del sector económico |


### va_sectorial_pais_bys.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Nombre de país o región de paises |
| es_agregacion | entero | Identificador de país: 0 o region de paises: 1 |
| particip_servicios_pib | real | Participación de los sectores de servicios en el PBI nacional. Para todos los países de la muestra. |


### va_sectorial_pais.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Nombre de país o región de paises |
| es_agregacion | entero | Identificador de país: 0 o region de paises: 1 |
| letra | alfanumerico | Agregación sectorial a nivel de grandes sectores (letra) |
| gran_sector | alfanumerico | Agregación sectorial a nivel de grandes sectores (descripción de la letra) |
| id_tipo_sector | entero | Indica si los sectores productivos son bienes o servicios (código). |
| tipo_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |
| particip_va_pib | real | Participación sectorial en el PBI nacional, por parte de cada sector productivo. Para todos los países de la muestra. |


### particip_va_intensivos_id_bys.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Nombre de país o región de paises |
| es_agregacion | entero | Identificador de país: 0 o region de paises: 1 |
| particip_bys_alta_intensidad | real | Participación sectorial en el PBI nacional de parte de los bienes y servicios de alta intensidad. Para todos los países de la muestra. |


### particip_sectorial_empleo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (fichas sectoriales), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (de fichas sectoriales), descripción abreviada. |
| share_sectorial | real | Participación en el empleo total, por parte de cada sector productivo. Para todo el país. |
| id_tipo_sector | entero | Indica si los sectores productivos son bienes o servicios (código). |
| tipo_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |


### particip_sectorial_empleoyvab.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (fichas sectoriales), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (de fichas sectoriales), descripción abreviada. |
| share_sectorial | real | Participación en el empleo total, por parte de cada sector productivo. Para todo el país. |
| id_tipo_sector | entero | Indica si los sectores productivos son bienes o servicios (código). |
| tipo_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |
| share_vab | real | Participación sectorial en el PBI nacional, por parte de cada sector productivo. Para todas las provincias de la muestra. |


### empleo_sectores_ggdc_1950_2018.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |
| gran_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |
| sector_codigo | alfanumerico | Sector económico (código) |
| sector_desc | alfanumerico | Sector económico (descripción) |
| empleo_miles | real | Cantidad de personas empleadas |
| share_empleo | real | Participación sectorial en el empleo por sector productivo |


### empn_tim_ocde.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |
| variable | alfanumerico | Indicador de unidad de la variable |
| gran_sector_id | entero | Código de gran sector |
| gran_sector_desc | alfanumerico | Descripción del gran sector |
| letra | alfanumerico | Letra de sector |
| letra_desc | alfanumerico | Descripción de la letra del sector |
| intensidad_id_ocde | alfanumerico | Categoría de intensidad de I+D |
| rama_rd | entero | Código de clasificación tecnológica |
| rama_rd_desc | alfanumerico | Descripción de clasificación tecnológica |
| ind_tim | alfanumerico | Codificación de la base del sector |
| ind_tim_desc_es | alfanumerico | Descripción del sector propio de la base |
| valor | real | Participación en el empleo de acuerdo a la categoría de intensidad tecnológica |


### particip_calificados_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario CAES), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario CAES), descripción abreviada. |
| calificacion_cod | entero | Clasificación según calificación (adhoc). Son 4 categorías: se considera calificado a profesional+técnico, semicalficado a operativo y no calificado a no calificado. También hay ocupados sin clasificación. |
| calificacion | alfanumerico | Clasificación según calificación (adhoc). Son 4 categorías: se considera calificado a profesional+técnico, semicalficado a operativo y no calificado a no calificado. También hay ocupados sin clasificación. |
| particip_calif | real | Porcentaje de personas calificadas sobre el total de ocupados de ese sector productivo. |


### particip_mujer_varon.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario CGI), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario CGI), descripción abreviada. |
| porc_mujeres | real | Porcentaje de mujeres sobre la fuerza laboral total. |
| porc_varones | real | Porcentaje de varones sobre la fuerza laboral total. |


### particip_mujer.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario CAES), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario CAES), descripción abreviada. |
| porc_mujeres | real | Porcentaje de mujeres sobre la fuerza laboral total. |


### vab_sectorial_granregion.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (INDEC), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (INDEC), descripción abreviada. |
| gran_region_id | entero | Código de la región de referencia. Son 3: Centro, Norte y Sur. Es una medida adhoc. |
| gran_region_desc | alfanumerico | Descripción de la región de referencia. Son 3: Centro, Norte y Sur. |
| share_vab_sectorial | real | Participación sectorial en el PBI nacional, por parte de cada sector productivo. Para todas las grandes regiones de la muestra. |


### vab_sectorial_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| provincia_id | entero | Código de la provincia de referencia. |
| provincia | alfanumerico | Descripción de la provincia de referencia. |
| gran_region_id | entero | Código de la gran región |
| gran_region_desc | alfanumerico | Descripción de la gran región |
| letra | alfanumerico | Agregación sectorial a nivel de letra (INDEC), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (INDEC), descripción abreviada. |
| tipo_sector | alfanumerico | Indica si los sectores productivos son bienes o servicios (descripción) |
| share_vab_sectorial | real | Participación sectorial en el PBI nacional, por parte de cada sector productivo. Para todas las provincias de la muestra. |


### productividad_internacional.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |
| productividad_tipo | alfanumerico | Categoría de productividad: por hora o por ocupado. |
| valor | real | Productividad en dólares a paridad de poder adquisitivo constantes de 2017 |


### pib_por_ocupado.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumérico | Código de país o región de países |
| pais_nombre | alfanumérico | Descripción de país o región de países |
| continente_fundar | alfanumerico | Descripción de continente al que pertenece el país |
| anio | entero | Año de referencia |
| pib_por_ocupado | real | PIB por ocupado, en dólares PPP de 2017 |


### va_por_trabajador.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (fichas sectoriales), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (de fichas sectoriales), descripción abreviada. |
| va_por_trabajador | real | Valor agregado por trabajador, en miles de pesos |
| indice_va_trab | real | Índice de valor agregado por trabajador. El promedio de la economía es = 100. |


### va_por_trabajador_pais.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país o región de países |
| iso3_desc_fundar | alfanumerico | Nombre de país o región de paises |
| es_agregacion | entero | Identificador de país: 0 o region de paises: 1 |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario TIVA OCDE traducido), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario TIVA OCDE traducido), descripción abreviada. |
| valor_relativo_arg | real | Índice de valor agregado por trabajador, relativo a Argentina (ARG base 100) |


### empresas_nacional.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| empresas | entero | Cantidad de firmas privadas que declaran empleo Sistema Integrado Previsional Argentino |


### sector_escala.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario INDEC-MTEYSS), letra. |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario INDEC-MTEYSS), descripción abreviada. |
| escala | real | Empleo registrado sobre firmas que declararon trabajadores |


### escala_salarios.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| indice_salario | real | Índice de salarios, promedio economía = 100. Para cada año. |
| letra | alfanumerico | Agregación sectorial a nivel de letra (diccionario INDEC-MTEYSS), letra. |
| anio | entero | Año de referencia |
| letra_desc_abrev | alfanumerico | Agregación sectorial a nivel de letra (diccionario INDEC-MTEYSS), descripción abreviada. |
| escala | real | Empleo registrado sobre firmas que declararon trabajadores |


### densidad_empresarial_depto.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| id_depto | entero | Código del departamento de referencia. |
| departamento | alfanumerico | Descripción del departamento de referencia. |
| provincia_id | entero | Código de la provincia de referencia. |
| provincia | alfanumerico | Descripción de la provincia de referencia. |
| densidad_emp | real | Cantidad de establecimientos por cada 1,000 habitantes |


### tasa_informalidad_tamanio_empresa.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| tamanio_cod | entero | Código del tamaño de empresa |
| tamanio_desc | alfanumerico | Descripción del tamaño de empresa |
| tasa_informalidad | real | Tasa de informalidad asalariada |


### densidad_nbi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| id_depto | entero | Código del departamento de referencia. |
| departamento | alfanumerico | Descripción del departamento de referencia. |
| provincia_id | entero | Código de la provincia de referencia. |
| provincia | alfanumerico | Descripción de la provincia de referencia. |
| region | alfanumerico | Descripción de la región de referencia. |
| densidad_emp | real | Cantidad de establecimientos por cada 1,000 habitantes |
| share_pb_nbi | real | Porcentaje de población con Necesidades Básicas Insatisfechas (NBI) |


### empleo_invdes_tim_ocde.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país o región de países |
| anio | entero | Año de referencia |
| intensidad_id_ocde | alfanumerico | Clasificación tecnológica |
| empleo | real | Personas empleadas por sector |
| share | real | Porcentaje |


