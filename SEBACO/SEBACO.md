## SEBACO 

### 01_ventas_afip.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Rama de actividad |
| share_ventas | real | Proporción de las ventas totales del país explicadas por SBC |


### 02_vbp_ssi_fundar.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| vbp_ssi_2022 | real | Valor bruto de producción de SSI a precios constantes de 2022 |
| prop_ssi_total | real | proporción sobre el VBP total del país |


### 03_vab_indec.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| vab | real | Proporción del VAB de SSI sobre el total de Valor Agregado Bruto de la economía |


### 04_exportacion_sbc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| exportaciones_sbc | real | Nivel de exportaciones en millones de dólares del complejo de SBC |
| prop_expo_sbc_servicios | real | Proporción de las exportaciones de SBC sobre las exportaciones totales de servicios |
| prop_expo_sbc_total | real | Proporción de las exportaciones de SBC sobre las exportaciones totales |


### 05_empleo_sbc_oede.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sbc | real | Empleados dentro de SBC |
| prop_sbc | real | Proporción del empleo total explicado por SBC |


### 06_empleo_sbc_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| provincia | alfanumerico | Provincia en la que se encuentra el empleo |
| anio | entero | Año de referencia |
| prop | real | Proporción del empleo de SBC explicado por cada provincia |


### 07_empleo_sbc_provincias_princ.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| provincia | alfanumerico | Provincia en la que se encuentra el empleo |
| anio | entero | Año de referencia |
| prop | real | Proporción del empleo de SBC explicado por cada provincia (Agrupadas) |


### 08_i_d_sbc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sector | alfanumerico | Rama de actividad |
| anio | entero | Año de referencia |
| prop | real | Proporción de la inversión en I+D sobre el total del gasto en I+D explicadas por las ramas de SBC |


### 09_composicion_sbc_rama.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| rama | alfanumerico | Rama de actividad |
| anio | entero | Año de referencia |
| prop_rama | real | Composición del empleo en SBC (proporción explicada por cada rama) |


### 10_empleo_x_rama_y_prop.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| rama | alfanumerico | Rama de actividad |
| anio | entero | Año de referencia |
| empleo | real | Cantidad de empleados por rama de SBC |
| sbc_perc | real | Proporción del empleo de una rama sobre el total de empleados en SBC |
| total_perc | real | Proporción del empleo de una rama sobre el total de empleados en el sector privado registrado |


### 11_ocupados_x_condicion.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| estado_ocupacional | alfanumerico | Situación ocupacional de los trabajadores |
| prop_ocupados | real | Proporción de trabajadores ocupados según condición en el sector de referencia |


### 12_salarios_sbc_y_desagregado.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector_sbc | alfanumerico | Rama de actividad |
| salario_promedio | real | Salario promedio constante del sector de SBC según rama |


### 13_ocupados_x_niveled.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| nivel | alfanumerico | Máximo nivel educativo alcanzado por los ocupados |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| prop_educ | real | Proporción de ocupados por nivel educativo según sector económico |


### 14_participacion_femenina_sbc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| prop_mujeres | real | Proporción de trabajadoras mujeres sobre total de trabajadores |


### 15_participacion_femenina_ssi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| prop_mujeres | real | Proporción de trabajadoras mujeres sobre total de trabajadores |


### 16_brecha_salarial_ssi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| periodo | entero | Año de referencia |
| brecha | real | Brecha salarial entre varones y mujeres en el sector de SSI |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |


### 17_tasa_teletrabajo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| prop_teletrabajo | real | Proporción de trabajadores que realizan tareas de teletrabajo en cada rama |


### 18_expo_impo_saldo_x_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| balanza | real | Saldo de la balanza comercial de cada sector de SBC en millones de dólares |
| exportaciones | real | Valor de las exportaciones de cada sector de SBC en millones de dólares |
| importaciones | real | Valor de las importaciones de cada sector de SBC en millones de dólares |


### 19_saldo_comex_x_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| sector | alfanumerico | Sector económico al que pertenecen los trabajadores |
| balanza | real | Saldo de la balanza comercial en millones de dólares según rama |


### 20_composicion_expo_sbc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| descripcion | alfanumerico | Rama de actividad |
| prop_sobre_sbc_expo | real | Composición de las exportaciones de SBC según relevancia de cada rama |


### 21_exportaciones_ssi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| exportaciones | real | Exportaciones de SSI |
| prop_sobre_expo_total | real | Proporción sobre las exportaciones totales del país |


### 22_participacion_expo_sbc.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año de referencia |
| prop_expo | real | Proporción de las exportaciones de SBC de cada país sobre el total mundial |


### 23_participacion_expo_ssi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año de referencia |
| prop_expo | real | Proporción de las exportaciones de SSI de cada país sobre el total mundial |


### 24_expo_x_socio_comercial_arg.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país |
| expo | real | Valor de las exportaciones hacia cada socio comercial de Argentina |


### 25_impo_x_socio_comercial_arg.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| iso3 | alfanumerico | Código de país |
| impo | real | Valor de las importaciones hacia cada socio comercial de Argentina |


