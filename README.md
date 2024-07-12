# Datos de Argendata

En este repositorio se comparten conjuntos de datos publicados en cada tópico de Argendata. Estos corresponden a la salida del proceso semi automatizado de [rerproductibilidad (ETL)](https://github.com/argendata/etl), equivalente a los datos producidos por investigadores [^2]. 

[^2]: El flujo de trabajo definido para la reproductibilidad cuenta con una librería de `R` que reune un conjunto de funciones para facilitar el flujo de trabajo con fuentes y recursos en Argendata [https://github.com/argendata/argendataR](https://github.com/argendata/argendataR)

En el siguiente esquema se muestra como ejemplo la organización de la infromación: **(i)** el sistema de archivos se organiza a partir de tópicos (`AGROPE`, `CAMCLI`, `COMEXT`, etc.); **(ii)** al interior de cada directorio se guardan las salidas del proceso de ETL (datos y metadatos). 

```
├── AGROPE
├── CAMCLI
├── COMEXT
│   ├── cambio_destinos_exportacion.csv
│   ├── cambio_destinos_exportacion.json
│   ├── cambio_origenes_importacion.csv
│   ├── cambio_origenes_importacion.json
│   ├── composicion_exportaciones_bienes_diferenciado_Bernini.csv
│   ├── composicion_exportaciones_bienes_diferenciado_Bernini.json
│   ├── composicion_exportaciones_bienes_regiones_mundo.csv
│   ├── composicion_exportaciones_bienes_regiones_mundo.json
│   ├── composicion_exportaciones_bienes_sectores_Brambilla_Porto.csv
│   ├── composicion_exportaciones_bienes_sectores_Brambilla_Porto.json
│   ├── composicion_exportaciones_bienes_sitc_seccion.csv
│   ├── composicion_exportaciones_bienes_sitc_seccion.json
│   ├── composicion_exportaciones_servicios_EBOPS_2digitos_agrupado.csv
│   ├── composicion_exportaciones_servicios_EBOPS_2digitos_agrupado.json
│   ├── composicion_importaciones_bienes_diferenciado_Bernini.csv
│   ├── composicion_importaciones_bienes_diferenciado_Bernini.json
│   ├── composicion_importaciones_bienes_regiones_mundo.csv
│   ├── composicion_importaciones_bienes_regiones_mundo.json
│   ├── composicion_importaciones_bienes_sectores_Brambilla_Porto.csv
│   ├── composicion_importaciones_bienes_sectores_Brambilla_Porto.json
│   ├── composicion_importaciones_bienes_sitc_seccion.csv
│   ├── composicion_importaciones_bienes_sitc_seccion.json
│   ├── exportaciones_bienes_servicios_millones_usd_constantes_2015.csv
│   ├── exportaciones_bienes_servicios_millones_usd_constantes_2015.json
│   ├── exportaciones_servicios_top_20_destinos.csv
│   ├── exportaciones_servicios_top_20_destinos.json
│   ├── indice_apertura_comercial.csv
│   ├── indice_apertura_comercial.json
│   ├── indice_cantidad_exportaciones_argentina.csv
│   ├── indice_cantidad_exportaciones_argentina.json
│   ├── indice_valores_unitarios_exportacion_bienes_2000.csv
│   ├── indice_valores_unitarios_exportacion_bienes_2000.json
│   ├── indice_volumen_exportaciones_bienes_2000.csv
│   ├── indice_volumen_exportaciones_bienes_2000.json
│   ├── participacion_exportaciones_bienes_servicios_mundo.csv
│   ├── participacion_exportaciones_bienes_servicios_mundo.json
│   ├── participacion_exportaciones_bienes_servicios_porcentaje_pib.csv
│   ├── participacion_exportaciones_bienes_servicios_porcentaje_pib.json
│   ├── participacion_exportaciones_servicios_porcentaje_exportaciones.csv
│   └── participacion_exportaciones_servicios_porcentaje_exportaciones.json
├── CRECIM
├── DESHUM
├── DESIGU
├── ESTPRO
├── INFDES
├── MERTRA
├── MINERI
├── POBREZ
├── PRECIO
├── SALING
├── SEBACO
└── TRANEN
 

```

En el ejemplo, para el tópico de **[Comercio Exterior](https://argendata.fund.ar/topico/comercio-exterior/)**(`COMEXT`) se visualizan archvios `.csv` y `.json` asociados a cada uno de los items (`cambio_destinos_exportacion` [^3], por ejemplo). El primero de ellos contiene los datos. El segundo también incluye los metadatos asociados (fuente de información, institución productora, fechas de procesamiento, etc.):

[^3]: El código que genera esta salida es parte del proceso de ETL y puede consultarse en el _script_ [`18_cambio_destinos_exportacion.R`](https://github.com/argendata/etl/blob/main/scripts/subtopicos/COMEXT/18_cambio_destinos_exportacion.R)


### `cambio_destinos_exportacion.csv`
```
"iso3","location_name_short_en","partner_code","partner_name_short_en","export_value_pca","export_value_pcb"
"AFG","Afghanistan","ANT","Netherlands Antilles","0",
"AFG","Afghanistan","AUT","Austria","0.688627518615602","0.0733990364249315"
"AFG","Afghanistan","BEL","Belgium","0","0.0683462241450678"
"AFG","Afghanistan","BGR","Bulgaria","0","0.00372820071862202"
"AFG","Afghanistan","CHE","Switzerland","2.41999320416714","0.188186688833644"
"AFG","Afghanistan","CHN","China","0.451026512726798","1.8664145222227"
"AFG","Afghanistan","COD","Congo (Democratic Republic of the)","0","0.00539090999076861"
"AFG","Afghanistan","CSK","Czechoslovakia","3.41910119179182",
"AFG","Afghanistan","DEU","Germany","15.53527024738","0.854150132334422"
"AFG","Afghanistan","DNK","Denmark","0.228550053266833","0.146499065976512"
```

Estos datos, que son los que se disponibilizan para la descarga de usuarios de Argendata, son procesados luego por [transformers](https://github.com/argendata/transformers) para servir de insumo para la graficación en el [Frontend](https://argendata.fund.ar/) [^1]. 



[^1]: Para este proceso se desarrolló una [librería para `Python`](https://github.com/argendata/data-transformers) que busca facilitar la escritura, ejecución, reproducibilidad y el versionado del código fuente que se realice para manipular datos estructurados para la graficación. Típicamente se trata de dar un formato estandarizado a los datos a través de acciones como el filtrado de valores o la selección / renombrado de variables. El [siguiente _transformer_](https://github.com/argendata/transformers/blob/main/COMEXT/COMEXT_g18_transformer.py) se corresponde con el ejemplo antes expuesto. 




