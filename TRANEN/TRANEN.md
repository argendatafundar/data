## TRANEN 

### matriz_prim_mundo_historic_larga.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| tipo_energia | alfanumerico | Tipo de energía |
| valor_en_twh | real | Energía en TWh |
| porcentaje | real | Porcentaje |


### matriz_prim_mundo_historic.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| tipo_energia | alfanumerico | Tipo de energía |
| valor_en_twh | real | Energía en TWh |
| porcentaje | real | Porcentaje |
| fuente_energia | alfanumerico | Fuente de energía |


### energia_baja_carbono.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_porcentaje | real | Porcentaje |


### generacion_hidro_twh.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| valor_en_twh | real | Generación hidroeléctrica en 2022 |
| anio | entero | Año |
| iso3 | alfanumerico | Código de país |


### generacion_nuclear_twh.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| valor_en_twh | real | Generación nucleoeléctrica en 2022 |
| anio | entero | Año |
| iso3 | alfanumerico | Código de país |


### capacidad_instalada_fv_gw.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_gw | real | Capacidad instalada fotovoltaica |


### capacidad_instalada_eolica_gw.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_gw | real | Capacidad instalada eólica |


### produccion_biocomb.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_twh | real | Producción de biocombustibles |


### produc_electricidad_fuente_mundo_twh.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| tipo_energia | alfanumerico | Tipo de energía |
| valor_en_twh | real | Energía en TWh |
| porcentaje | real | Porcentaje |


### potencia_instalada_renov_regional.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| region | alfanumerico | Región |
| tipo_energia | alfanumerico | Tipo de energía renovable |
| valor_en_mw | entero | Energía en MW |
| porcentaje | real | Porcentaje |


### identidad_kaya_mundo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| energia_por_unidad_pib_kwh | real | Intensidad energética (por unidad de PIB medido en dólares de 2011 PPA) |
| pib_per_cap_usd_ppa_2011 | real | PIB per cápita en dólares PPA 2011 |
| poblacion | entero | Población argentina |
| emision_anual_co2_ton | real | Emisiones anuales de CO2 |
| emision_anual_kgco2_por_kwh | real | Intensidad de carbono (CO2/kWh) |
 | emision_anual_kgco2_por_kwh | real | Intensidad de carbono (CO2/energía) |


### intensidad_energ_mundo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_kwh_por_dolar | real | Consumo energético por unidad de PIB (en dólares PPA 2011) |


### intensidad_carbono_electri_mundo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| iso3 | alfanumerico | Código de país |
| anio | entero | Año |
| valor_en_gco2_por_kwh | real | Intensidad de carbono de la electricidad (por kWh) |


