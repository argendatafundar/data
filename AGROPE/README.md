## AGROPE 

### [participacion_agropecuario.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/participacion_agropecuario.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | año |
| participacion_agro | real | Cociente entre el PBI Agropecuario y el PBI Total de Argentina |


### [pbi_agro.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/pbi_agro.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pbi_agro_pcons | entero | PBI Agricultura, ganadería, caza y silvicultura en millones de pesos a precios constantes de 2004 |


### [apertura_cuentas_actividad_agropecuaria.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/apertura_cuentas_actividad_agropecuaria.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| cuenta | alfanumerico | Subrama de actividad económica de Agricultura, ganadería, caza y silvicultura |
| participacion_pbi | real | Cociente entre el valor agregado de cada Subrama de actividad económica dentro de Agricultura, ganadería, caza y silvicultura y PBI |


### [agro_global.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/agro_global.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3c | alfanumerico | Código país Banco Mundial |
| pais | alfanumerico | Nombre de país |
| anio | entero | Año de referencia |
| va_agro_sobre_pbi | real | Valor agregado de agricultura, ganadería, caza y pesca sobre el PBI |


### [PBG_participacion_agro_provincia_evolucion.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/PBG_participacion_agro_provincia_evolucion.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| nom_pcia | alfanumerico | Nombre de la provincia |
| valor | real | Participación del PIB agropecuario provincial en el PIB provincial |
| cod_pcia | entero | Identificador provincia |


### [share_cultivos.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/share_cultivos.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cultivo | alfanumerico | Cultivo |
| campania | alfanumerico | Ciclo temporal al que corresponde el cultivo |
| q_total | entero | Producción total por cultivo |
| share | real | Participación de la producción de cada cultivo en la producción total de todos los cultivos |


### [produccion_principales_cultivos.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_principales_cultivos.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cultivo | alfanumerico | Categoría cultivo (Maíz, Soja, Trigo) |
| campania | alfanumerico | Período temporal agrícola |
| q_total | real | Producción Total del país |


### [superficie_sembrada_principales_cultivos.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/superficie_sembrada_principales_cultivos.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cultivo | alfanumerico | Categoría cultivo (Maíz, Soja, Trigo) |
| campania | alfanumerico | Período temporal agrícola |
| supsem_total | real | Superficie Sembrada por cultivo (hectáreas) |


### [rindes_principales_cultivos.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/rindes_principales_cultivos.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cultivo | alfanumerico | Categoría cultivo (Maíz, Soja, Trigo) |
| campania | alfanumerico | Período temporal agrícola |
| rindes_avg | real | Rinde promedio anual por cultivo en Kg por hectárea |


### [rindes_maiz_internacional.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/rindes_maiz_internacional.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3_desc_fundar | alfanumerico | Pais |
| iso3 | alfanumerico | Código País |
| anio | entero | Año |
| rindes | real | Rendimientos Promedio del cultivo de maíz en Toneladas por hectárea |
| rindes_maiz_ma5 | real | Media móvil 5 años Rendimiento del cultivo de maíz |


### [rindes_soja_internacional.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/rindes_soja_internacional.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3_desc_fundar | alfanumerico | Pais |
| iso3 | alfanumerico | Código País |
| anio | entero | Año |
| rindes | real | Rendimientos Promedio del cultivo de soja en Toneladas por hectárea |
| rindes_soja_ma5 | real | Media móvil 5 años Rendimiento del cultivo de soja |


### [rindes_trigo_internacional.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/rindes_trigo_internacional.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3_desc_fundar | alfanumerico | Pais |
| iso3 | alfanumerico | Código País |
| anio | entero | Año |
| rindes | real | Rendimientos Promedio del cultivo de trigo en Toneladas por hectárea |
| rindes_trigo_ma5 | real | Media móvil 5 años Rendimiento del cultivo de trigo |


### [superficie_agricultura_paises_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/superficie_agricultura_paises_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| anio | entero | Año |
| valor | real | Superficie destinada a cultivos en miles de hectáreas |


### [produccion_soja_paises_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_soja_paises_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| anio | entero | Año |
| valor | real | Producción de soja en toneladas |


### [produccion_maiz_paises_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_maiz_paises_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| anio | entero | Año |
| valor | real | Producción de maiz en toneladas |


### [produccion_carne_tipos_arg_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_carne_tipos_arg_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| tipo_carne | alfanumerico | Tipo de carne producida en Argentina |
| valor | real | Toneladas producidas |


### [consumo_carne_tipos_arg_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/consumo_carne_tipos_arg_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| grupo_carne | alfanumerico | tipo de carne consumida en Argentina (bovina, porcina, aviar, caprina y pescado) |
| valor | real | kilogramos per cápita de carne consumida al año |


### [consumo_carne_tipos_mundo_2020.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/consumo_carne_tipos_mundo_2020.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3_desc_fundar | alfanumerico | Nombre País |
| iso3 | alfanumerico | Codi ISO3 país |
| tipo_carne | alfanumerico | tipo de carne (aviar, capirina, porcina, vacuna, pescado, otras) |
| valor | real | kilogramos per cápita de carne consumida al año |


### [produccion_global_carne_bovina_2021.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_global_carne_bovina_2021.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| valor | real | Produccion de carne bovina en toneladas |


### [produccion_global_carne_aviar_2021.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_global_carne_aviar_2021.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| valor | real | Produccion de carne aviar en toneladas |


### [produccion_global_carne_bovina_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_global_carne_bovina_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| anio | entero | Año |
| valor | real | Producción de carne bovina en toneladas |


### [share_carne_expo_paises_seleccionados_1962_2021.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/share_carne_expo_paises_seleccionados_1962_2021.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| share_expo | real | participacion exportaciones bovinas en total global |
| iso3 | alfanumerico | Codi ISO3 país |
| pais | alfanumerico | Nombre País |


### [share_carne_expo_argentinas_1962_2021.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/share_carne_expo_argentinas_1962_2021.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año |
| iso3 | alfanumerico | Codi ISO3 país |
| share_expo | real | participacion exportaciones bovinas argentinas en total global |
| product | alfanumerico | nombre del producto exportado |
| pais | alfanumerico | nombre del país |


### [stock_bovina_regiones_argentina.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/stock_bovina_regiones_argentina.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| region | alfanumerico | Regiones argentinas (NOA, NEA, Cuyo, Patagonia, Pampeana) |
| valor | real | stock bovino en cabezas |


### [participacion_PIB_pesca_PIB_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/participacion_PIB_pesca_PIB_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| valor | real | Participación del PIB pesquero dentro del PIB argentino a precios corrientes |
| nota | alfanumerico | Aclaración sobre si es valor oficial o estimado |


### [pesca_especie_arg_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/pesca_especie_arg_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| grupo_especie | alfanumerico | Especie de producto de mar (crustaceos, moluscos y peces) |
| valor | real | toneladas de peso vivo |


### [consumo_peces_percapita_global_2020.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/consumo_peces_percapita_global_2020.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| pescado_mariscos | real | kilogramos per cápita de carne consumida al año |


### [exportaciones_pesca_argentina_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/exportaciones_pesca_argentina_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| valor | real | Exportaciones en millones de dolares |


### [produccion_acuicultura_argentina_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_acuicultura_argentina_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| valor | real | toneladas de peso vivo |


### [produccion_acuicultura_global_2021.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/produccion_acuicultura_global_2021.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Identificador ISO3 |
| iso3_desc_fundar | alfanumerico | Nombre país |
| valor | real | toneladas de peso vivo |


### [participacion_CAA_PIB_arg_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/participacion_CAA_PIB_arg_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| valor | real | Participación del VAB de las cadenas agroindustriales en el PIB argentino |


### [participacion_tipos_CAA_VAB.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/participacion_tipos_CAA_VAB.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cadena | alfanumerico | Tipo de cadena agroidnustrial |
| valor | real | Participación dentro del VAB de cadenas agroindustriales |


### [evolucion_vab_constantes_tipo_cadenas.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/evolucion_vab_constantes_tipo_cadenas.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| cadena | alfanumerico | Tipo de cadena agroidnustrial |
| anio | entero | Año |
| valor | real | Valor agregado en millones pesos constantes de 2007 |


### [drawing_data.geojson](https://github.com/argendatafundar/data/blob/main//AGROPE/drawing_data.geojson)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| id_provincia | entero | Identificador de la provincia |
| nombres_provincia | alfanumerico | Nombre de la provincia |
| cadena | alfanumerico | Tipo de cadena agroalimentaria |
| valor | real | Participacion del VAB de la cadena provincial en el total del VAB de la cadena |
| id_cadena | entero | Identificador de la cadena |
| geometry | polígono | geolocalización de la provincia |


### [insercion_internacional_CAA.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/insercion_internacional_CAA.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tipo_cadena | alfanumerico | Tipo de cadena agroidnustrial |
| valor | real | Cociente entre VBP y valor exportado |


### [comex_arg_agroindustria_MOA_PP_evo.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/comex_arg_agroindustria_MOA_PP_evo.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| productos_primarios | real | Exportaciones en millones de dolares |
| moa | real | Exportaciones en millones de dolares |
| participacion_expo_totales | real | Participación exportaciones agroindustriales en el total de exportaciones nacionales |


### [indices_precios_exportacion.csv](https://github.com/argendatafundar/data/blob/main//AGROPE/indices_precios_exportacion.csv)

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| producto_exportacion | alfanumerico | Producto exportado |
| valor | real | índice de precios de exportacion con base 2004 = 100 |


