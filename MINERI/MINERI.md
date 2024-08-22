## MINERI 

### pbi_minero.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| petroleo_mineria | real | Participación del VAB de Extracción minas y canteras en el PBI a precios corrientes |
| mineria | real | Paricipación de Extracción de minerales metalíferos. Explotación de minas y canteras n.c.p. sobre el PBI a precios corrientes |


### minerales_vbp_mundial.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| codigo_pais | alfanumerico | Codigo país ISO3C |
| nombre_pais | alfanumerico | Nombre de País |
| share | real | Participación del mayor productor en la producción mundial |
| mineral | alfanumerico | Nombre de Mineral |
| tamanio_mercado | real | Tamaño de Mercado por mineral calculado como precio por producción mundial |


### expo_por_sectores.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| sector | alfanumerico | Sector Minero (Metalífero, No Metalífero, Piedras preciosas y semipreciosas, Rocas de Aplicación y otros) |
| exportaciones_sector_perc | real | Exportaciones de minerales por sector en relación a las exportaciones nacionales totales |


### expo_mineras_por_grupo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| grupo_nuevo | alfanumerico | Clasificación por grupo de minerales |
| expo_grupo | real | Exportaciones en dólares norteamericanos |


### importaciones_por_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| sector | alfanumerico | Sector minero de Importación |
| importaciones_sector_perc | real | Importaciones de minerales por sector en relación a las exportaciones nacionales totales |


### importaciones_por_grupo.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| grupo_nuevo | alfanumerico | Grupo de minerales |
| impo_grupo | real | Importaciones CIF en dólares norteamericanos |


### balanza_comercial_minera.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| exportaciones_mineras | real | Exportaciones totales del sector minero en dólares |
| importaciones_mineras | real | Importaciones totales del sector minero en dólares |
| saldo_comercial_minero | real | Exportaciones menos Importaciones del sector minero - Saldo Comercial en dólares |


### precios_metales.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| fecha | alfanumerico | Fecha |
| variable | alfanumerico | Es el tipo de medida índice o dólares por unidad de medida |
| valor | real | Valor de la variable. |


### precios_metales_real.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| fecha | alfanumerico | Fecha |
| variable | alfanumerico | Es el tipo de medida índice o dólares constantes por unidad de medida |
| valor | real | Valor de la variable. |


### peso_va_min_por_provincia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| provincia | alfanumerico | Provincia |
| anio | entero | Año |
| vab_min_vab_total_prov | real | Valor Agregado Bruto Minería a precios básicos a pesos constantes de 2004 como porcentaje del Valor Agregado Bruto a precios básicos a pesos constantes de 2004 total de la provincia |


### dist_provincial_pbi_minero.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| provincia | alfanumerico | Nombre de Provincia |
| vab_min_provincial | real | Valor Agregado Bruto a precios básicos (Extracción de minerales metalíferos. Explotación de  minas y canteras n.c.p.) en millones de pesos a precios constantes de 2004 |


### exportaciones_mineras_provinciales.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| provincia | alfanumerico | Nombre de Provincia |
| exportaciones | alfanumerico | Tipo de exportación |
| fob | entero | Valor Fob de exportaciones |


### empleo_minero.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| anio | entero | Año |
| empleo_minero_perc_formal_total | real | Empleo Minero como porcentaje del total de empleo de la economía OEDE |
| empleo_base | alfanumerico | Empleo según base de datos (OEDE Total, OEDE Minería y SIACAM Minería empalme) |
| cantidad_puestos | real | Cantidad de Puestos de Trabajo |


### min_comp_categoria_ocupacional_rama.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| rama_actividad | alfanumerico | Rama de Actividad económica |
| categoria_ocupacional | alfanumerico | Categoría ocupacional |
| porcentaje_sobre_total_rama | real | Participación de cada categoría ocupacional sobre el total de la rama |


### empleo_genero.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| fecha | alfanumerico | fecha |
| tasa_feminizacion | real | Cantidad de Puestos de Trabajo mujeres en el sector minero como porcentaje del empleo minero total |


### tasa_feminizacion_sector.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sector | alfanumerico | Sector de la economía (letra del CIIU rev. 3). Para minería (2 dígitos del CIIU rev. 3). |
| tasa_feminizacion | real | Participación laboral de las mujeres sobre el total de empleo sectorial |


### desc_ventas_min_metalifera.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| destino | alfanumerico | Destino de las ventas de la minería metalífera (Local o Externo) |
| concepto | alfanumerico | Descripción de la venta |
| porcentaje_total | real | Porcentaje de las ventas por concepto sobre el total (2017-2019) |


### compras_sector_minero_rama.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| rama_vendedora | alfanumerico | Rama Económica proveedora del sector minero |
| porcentaje_compra_sector_minero | real | Participación de compras totales por rama |


### importaciones_directas_mineria.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| sector | alfanumerico | Sector de la economía |
| ciiu_3_4c_desc | alfanumerico | Descripción CIIU rev 3 a 4 dígitos |
| monto | entero | Importaciones directas 2019 en millones de pesos |
| perc_total | real | Porcentaje de importaciones sobre el total |


### crecimiento_demanda_minerales_2040.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| mineral | alfanumerico | Tipo de Mineral |
| escenario_desarrollo_sostenible | real | Crecimiento proyectado de demanda por mineral a 2040 si se mantiene el aumento de la temperatura global por debajo de 1.8 grados centigrados de acuerdo a los ODS (2020=1) |
| escenario_base | real | Crecimiento proyectado de demanda por mineral a 2040 en base a un escenario conservador considerando solo las políticas actuales y en desarrollo para alcanzar las metas declaradas (2020=1) |


### minerales_criticos_energia.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tipo_energia | alfanumerico | Fuente de energía eléctrica |
| mineral_critico | alfanumerico | Mineral crítico |
| mineral_utilizado | real | Cantidad utilizada de mineral para generación eléctrica |


### minerales_criticos_vehiculos.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| tipo_auto | alfanumerico | Tipo de auto según combustión del motor |
| mineral_critico | alfanumerico | Mineral crítico |
| mineral_utilizado_kg_por_vehiculo | real | Cantidad utilizada de mineral en kg para la fabricación del vehículo completo (Batería, motor y carrocería) |


### ranking_minerales_argentina.csv

|**Variable**|**Tipo de dato**|**Descripcion**|
|:-------------:|:-------------:|:-------------:|
| mineral | alfanumerico | Nombre de Mineral |
| unidad_medida | alfanumerico | Unidad de medida de la producción |
| ranking | alfanumerico | Número correspondiente a la posición de Argentina como productor mundial |
| produccion | entero | Producción |


