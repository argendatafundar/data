## SALING 

### ISA_ipcf_it1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| ipcf_index | real | Índice evolución ingreso per cápita familiar (2003-II = 100) |


### ISA_ipcf-LAC_it1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| country_code | alfanumerico | Código ISO3 de país |
| year | entero | Año calendario |
| ipcf_promedio | real | Ingreso per cápita familiar promedio en dólares a PPA 2017 |


### ISA_ipcf-LAC_it2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| country_code | alfanumerico | Código ISO3 de país |
| year | entero | Año calendario |
| ipcf_promedio | real | Ingreso per cápita familiar promedio en dólares a PPA 2017 |


### ISA_regiones-ipcf_it1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| region | alfanumerico | Región geográfica |
| deflactor | alfanumerico | Deflactor usado para los ingresos |
| indice | real | Valor relativo del ingreso regional respecto al nacional en 2023-I |


### ISA_regiones-ipcf_it2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| region | alfanumerico | Región geográfica |
| indice | real | Valor relativo del ingreso regional respecto al nacional en 2003-II |


### ISA_composicion-ipcf_it1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| proporcion | real | Proporción del ingreso total familiar representada por el ingreso laboral |


### ISA_composicion-ipcf_it2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| decil | alfanumerico | Decil de la distribución del ingreso per capita familiar al que pertenece el hogar |
| fuente | alfanumerico | Fuente de ingreso |
| proporcion | real | Proporción representada por las distintas fuentes de ingreso en el ingreso total |


### ISA_composicion-ipcf_it3.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| edad_jefe | alfanumerico | Grupo etario al que pertenece el jefe de hogar |
| fuente | alfanumerico | Fuente de ingreso |
| proporcion | real | Proporción representada por las distintas fuentes de ingreso en el ingreso total |


### ISA_composicion-ipcf_it4.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| genero | alfanumerico | Género del jefe de hogar |
| proporcion | real | Proporción del ingreso total familiar representada por el ingreso laboral |


### ISA_composicion-ipcf_it5.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| year | entero | Año calendario |
| semestre | entero | Semestre |
| fuente | alfanumerico | Fuente de ingreso |
| indice | real | Valor del ingreso real promedio en las distintas fuentes de ingreso (2003-II = 100) |


### ISA_salario_real_i1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| variable | alfanumerico | Variable considerada: Ingreso laboral horario a precios de diciembre de 2016 - Base 1992 = 100 (ingresohorario)/Ingreso laboral mensual de todos los trabajadores captados en la EPH a precios de diciembre de 2016 - Base 1992 = 100 (ingreso mensual) |
| valor | real | Valor que toma la variable considerada |


### ISA_salario_real_i2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| mes | entero | Mes del año calendario |
| ano | entero | Año calendario |
| indice | real | Valor mensual del salario calculado a partir del Índice de Salarios publicado por INDEC, en términos reales, deflactado por el IPC nivel general de INDEC (octubre 2016=100) |


### ISA_salario_real_i3.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| salario | real | Salario medio real a pesos constantes de 2014 |


### ISA_salarios_mundo_i1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| pais | alfanumerico | Código ISO 3 país |
| salariohorario | real | Valor promedio por país del ingreso laboral por hora de la ocupación principal de todos los trabajadores expresados en dólares a paridad de poder de compra (PPP 2011) |


### ISA_salarios_mundo_i2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| variable | alfanumerico | Variable considerada: valor propmedio del ingreso laboral por hora de la ocupación principal de todos los trabajadores, cualquiera sea su condición de empleo, expresados en dólares a paridad de poder de compra (PPP 2011) para América Latina (AmericaLatina) / y para Argentina (Argentina) |
| valor | real | Valor que toma la variable considerada |


### ISA_tipo_empleo_i1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| variable | alfanumerico | Ingreso mensual en términos reales por tipo de empleo. Las categorías de empleo son: Empresarios/Asalariadosfirmasgrandes/Asalariadospúblico/Profesionales/Asalariadospequeñas/Cuentapropistas |
| valor | entero | Valor que toma la variable considerada |


### ISA_tipo_empleo_i2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| mes | entero | Mes del año calendario |
| variable | alfanumerico | Variable considerada: Valor mensual del salario por tipo de empleo, calculado a partir del Índice de Salarios publicado por INDEC, en términos reales, deflactado por el IPC nivel general de INDEC (octubre 2016=100). Los tipos de empleo son: Privadoregistrado/Sectorpúblico/Privadonoregistrado |
| valor | real | Valor que toma la variable considerada |


### ISA_tipo_empleo_i3.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| pais | alfanumerico | Pais |
| variable | alfanumerico | Variable considerada: Valor promedio del ingreso laboral mensual en distintos tipos de trabajo: Empleadores, Asalariadosgrandes, publico, profesionales, Asalariadosmicro,Cuentapropia,Media |
| valor | real | Valor que toma la variable considerada |


### ISA_salarios_region_i1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| region | alfanumerico | Región argentina |
| variable | alfanumerico | Ingreso laboral mensual de todos los trabajadores entre 25 y 65 años captados por la EPH, por nivel educativo tomando como valor base (=100) el promedio nacional. |
| valor | real | Valor que toma la variable considerada |


### ISA_salarios_region_i2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano_trim | alfanumerico | Año - trimestre calendario |
| variable | alfanumerico | Región considerada para captar el ingreso laboral mensual promedio de todos los trabajadores entre 25 y 65 años, en cualquier tipo de empleo, captados por la EPH. |
| valor | real | Valor que toma la variable considerada |


### ISA_edad_genero_i1.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| edad | entero | Edad de los individuos |
| variable | alfanumerico | Variable considerada: género y tipo de gráfico que computa valor medio de los ingresos laborales por hora en la ocupación principal de todos los trabajadores: Hombres (hombres1)/Suavizado de hombres(hombres2)/Mujeres(mujeres1)/Suavizado de mujeres (mujeres2) |
| valor | entero | Valor que toma la variable considerada |


### ISA_edad_genero_i2.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| edad | entero | Edad de los individuos |
| variable | alfanumerico | Variable considerada: género y tipo de gráfico que computa valor medio de los ingresos laborales por hora en la ocupación principal de todos los trabajadores: Hombres (hombres1)/Suavizado de hombres(hombres2)/Mujeres(mujeres1)/Suavizado de mujeres (mujeres2) |
| valor | entero | Valor que toma la variable considerada |


### ISA_edad_genero_i3.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| ano | entero | Año calendario |
| variable | alfanumerico | Variable considerada: ingreso laboral mensual en términos reales de todos los trabajadores captados por la EPH por género y grupo etario |
| valor | entero | Valor que toma la variable considerada |


### salario_real_base1970.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| salario_real_base1970 | entero | Indice con base 100 en el año 1970, del salario real promedio |


### salario_real_ppa2017_ceped.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Codigo ISO Alpha 3 |
| anio | entero | Año de referencia |
| salario_real_ppa_consumo_privado_2017 | real | Salario real en dólares de paridad de poder adquisitivo de 2017 (PPA de consumo privado) |


### prima_formalidad_argentina.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año de referencia |
| tipo_prima | alfanumerico | Tipo de prima de referencia ("Controlando por variables sociodemográficas" ; "Sin control por otras variables") |
| prima | real | Brecha en el salario horario entre asalariados registrados y asalariados no registrados |


