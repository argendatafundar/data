## ACECON 

### 1_pib_pibpc_pob_arg_esp.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais | alfanumerico | País |
| iso3 | alfanumerico | País Código ISO3 |
| pbi_precios_constantes_base1900 | real | Producto Bruto Interno, Precios Constantes (1900=100) |
| pbi_per_capita_precios_constantes_base1900 | real | Producto Bruto Interno per cápita, Precios Constantes (1900=100) |
| poblacion_base1900 | real | Población (1900=100) |


### 2_pibpc_salud_edu.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| pais | alfanumerico | País |
| iso3 | alfanumerico | País Código ISO3 |
| anios_de_educacion | real | Años de educación promedio |
| esperanza_de_vida_al_nacer | real | Esperanza de vida al nacer |
| pbi_per_capita | entero | PBI per cápita PPA |


### 3_pibpc_prec_cons.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pbi_per_capita_pconst2004 | real | PBI per cápita Precios Constantes ($ de 2004) |


### 4_pibpc_prop_eeuu.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais | alfanumerico | País |
| iso3 | alfanumerico | Código ISO3 |
| pib_per_capita_ppa_porcentaje_eeuu | real | PBI per cápita PPA como porcentaje del de EEUU |


### 5_pibpc_prop_arg.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais | alfanumerico | País |
| iso3 | alfanumerico | Código ISO3 |
| pbi_per_capita_ppa_porcentaje_argentina | real | PBI per cápita PPA como porcentaje del de Argentina |


### 6_pib_comp_dem_ag.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| comp_dem_ag | alfanumerico | Componente de la demanda agregada |
| valor | real | Valor del PIB |


### 7_pib_comp_va.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| sector | alfanumerico | Sector económico |
| valor | real | Valor del PIB |


### 8_pib_dist.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| remuneracion_al_trabajo_asalariado | real | Remuneración al trabajo asalariado |
| otros | real | Otros |


### 9_pibpc_ppa_log_1950.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais_o_region | alfanumerico | País o Región |
| pbi_per_capita_ppa | real | PBI per cápita PPA |


### A1_inb_pib.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais | alfanumerico | País |
| iso3 | alfanumerico | País Código ISO3 |
| diferencia_inb_pbi | real | Diferencia INB PBI como porcentaje del PBI |


### A2_pib_prec_corr_prec_cons.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pbi_precios_const2004 | real | PBI precios constantes (millones de $ de 2004) |
| pbi_precios_corr | real | PBI precios corrientes (millones de $) |


### A3_ipc_ipi.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| ipc | real | Índice de Precios al Consumidor (IPC): Variación porcentual de promedio anual |
| ipi | real | Índice de Precios Implícitos (IPI): Variación porcentual de promedio anual |


### A4_efecto_bs.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| pais | alfanumerico | País |
| iso3 | alfanumerico | País Código ISO3 |
| pbi_per_capita_usd | entero | PBI per cápita USD 2017 |
| precios_eeuu100 | real | Nivel de Precios 2017. EEUU=100. |


### A5_pibpc_propeeuu_ppa_usd.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| pais | alfanumerico | País |
| iso3 | alfanumerico | País Código ISO3 |
| pbi_per_capita_ppa_porcentaje_eeuu | real | PBI per cápita PPA como porcentaje del de EEUU |
| pbi_per_capita_usd_porcentaje_eeuu | real | PBI per cápita USD como porcentaje del de EEUU |
| ppa_usd | real | Factor PPA/USD |


### A6_uci.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| uci | real | Utilización de la Capacidad Instalada en la Industria Manufacturera |


### A7_pib_tendencia_ciclo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| trimestre | entero | Trimestre |
| serie | alfanumerico | Serie: pib tendencia, pib ciclo, pib |
| valor | real | Valor del PIB |


### A8_pib_desestacionalizado.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| trimestre | alfanumerico | Trimestre |
| anio | entero | Año |
| pbi | real | PBI |
| pbi_desestacionalizado | real | PBI desestacionalizado |


