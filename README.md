<div align='left'>
    <a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/0730507d-59cf-4905-95f2-01469c091b08">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/ca91a731-6d35-4028-a5f6-bdd8e15d03aa">
    <img src="fund.ar"></img>
  </picture>
</a>
</div>

En este repositorio se comparten conjuntos de datos publicados en cada tópico de Argendata. Estos corresponden a la salida del proceso semi automatizado de [rerproductibilidad (ETL)](https://github.com/argendata/etl), equivalente a los datos producidos por investigadores [^2]. 

En el siguiente esquema se muestra como ejemplo la organización de la infromación: **(i)** el sistema de archivos se organiza a partir de tópicos (`AGROPE`, `CAMCLI`, `COMEXT`, etc.); **(ii)** al interior de cada directorio se guardan las salidas del proceso de ETL (datos y metadatos). 

<div align='center', width="100%">
    <table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>categoria</th>
      <th>topico</th>
      <th>codigo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/ambiente">Ambiente</a></td>
      <td><a href="https://argendata.fund.ar/topico/emisiones-de-gases-de-efecto-invernadero/">Emisiones de gases de efecto invernadero</a></td>
      <td>CAMCLI</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/ambiente">Ambiente</a></td>
      <td><a href="https://argendata.fund.ar/topico/cambio-climatico/">Cambio climático</a></td>
      <td>CAMCLI</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/ambiente">Ambiente</a></td>
      <td><a href="https://argendata.fund.ar/topico/transicion-energetica/">Transición energética</a></td>
      <td>TRANEN</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/macroeconomia">Macroeconomía</a></td>
      <td><a href="https://argendata.fund.ar/topico/crecimiento/">Crecimiento</a></td>
      <td>CRECIM</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/macroeconomia">Macroeconomía</a></td>
      <td><a href="https://argendata.fund.ar/topico/inflacion/">Inflación</a></td>
      <td>PRECIO</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/desarrollo">Desarrollo</a></td>
      <td><a href="https://argendata.fund.ar/topico/pobreza/">Pobreza</a></td>
      <td>POBREZ</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/desarrollo">Desarrollo</a></td>
      <td><a href="https://argendata.fund.ar/topico/estructura-productiva/">Estructura productiva</a></td>
      <td>ESTPRO</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/desarrollo">Desarrollo</a></td>
      <td><a href="https://argendata.fund.ar/topico/desarrollo-humano/">Desarrollo humano</a></td>
      <td>DESHUM</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/desarrollo">Desarrollo</a></td>
      <td><a href="https://argendata.fund.ar/topico/comercio-exterior/">Comercio exterior</a></td>
      <td>COMEXT</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/desarrollo">Desarrollo</a></td>
      <td><a href="https://argendata.fund.ar/topico/desigualdad/">Desigualdad</a></td>
      <td>DESIGU</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/sectores-productivos">Sectores productivos</a></td>
      <td><a href="https://argendata.fund.ar/topico/agroindustria/">Agroindustria</a></td>
      <td>AGROPE</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/sectores-productivos">Sectores productivos</a></td>
      <td><a href="https://argendata.fund.ar/topico/servicios-basados-en-el-conocimiento/">Servicios basados en el conocimiento</a></td>
      <td>SEBACO</td>
    </tr>
    <tr>
      <td><a href="https://argendata.fund.ar/categorias/sectores-productivos">Sectores productivos</a></td>
      <td><a href="https://argendata.fund.ar/topico/mineria/">Minería</a></td>
      <td>MINERI</td>
    </tr>
    <tr>
      <td><a href='https://argendata.fund.ar/categorias/trabajo-e-ingresos/'>Trabajo e ingresos</a></td>
      <td><a href="https://argendata.fund.ar/topico/salarios-e-ingresos/">Salarios e ingresos</a></td>
      <td>SALING</td>
    </tr>
    <tr>
      <td><a href='https://argendata.fund.ar/categorias/trabajo-e-ingresos/'>Trabajo e ingresos</a></td>
      <td><a href="https://argendata.fund.ar/topico/trabajo-y-participacion-laboral/">Trabajo y participación laboral</a></td>
      <td>MERTRA</td>
    </tr>
    <tr>
      <td><a href='https://argendata.fund.ar/categorias/trabajo-e-ingresos/'>Trabajo e ingresos</a></td>
      <td><a href="https://argendata.fund.ar/topico/informalidad-y-desempleo/">Informalidad y desempleo</a></td>
      <td>INFDES</td>
    </tr>
  </tbody>
</table>
</div>

---
## Índice

- [Actividad económica](#actividad-económica)
- [Agroindustria](#agroindustria)
- [Cambio climático y emisiones de gases de efecto invernadero](#cambio-climático-y-emisiones-de-gases-de-efecto-invernadero)
- [Comercio exterior](#comercio-exterior)
- [Crecimiento](#crecimiento)
- [Desarrollo humano](#desarrollo-humano)
- [Desigualdad](#desigualdad)
- [Estructura productiva](#estructura-productiva)
- [Informalidad y desempleo](#informalidad-y-desempleo)
- [Trabajo y participación laboral](#trabajo-y-participación-laboral)
- [Minería](#minería)
- [Pobreza](#pobreza)
- [Inflación](#inflación)
- [Salarios e ingresos](#salarios-e-ingresos)
- [Servicios basados en el conocimiento](#servicios-basados-en-el-conocimiento)
- [Transición energética](#transición-energética)
---
## [Actividad económica](./ACECON/)
[(volver al índice)](#índice)

| titulo                                                    | link                                                                                                                                                       |
|:----------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| La demanda agregada de Argentina y su relación con el PIB | [la-demanda-agregada-de-argentina-y-su-relacion-con-el-pib](https://argendata.fund.ar/graficos/la-demanda-agregada-de-argentina-y-su-relacion-con-el-pib/) |
| El PIB por sectores en Argentina                          | [el-pib-por-sectores-en-argentina](https://argendata.fund.ar/graficos/el-pib-por-sectores-en-argentina/)                                                   |
| Participación de los factores productivos en el PIB       | [participacion-de-los-factores-productivos-en-el-pib](https://argendata.fund.ar/graficos/participacion-de-los-factores-productivos-en-el-pib/)             |

## [Agroindustria](./AGROPE/)
[(volver al índice)](#índice)

| titulo                                                                             | link                                                                                                                                                                                                         |
|:-----------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Principales productos exportados vinculados al sector agroindustrial               | [principales-productos-exportados-vinculados-al-sector-agroindustrial-2](https://argendata.fund.ar/graficos/principales-productos-exportados-vinculados-al-sector-agroindustrial-2/)                         |
| Principales exportaciones argentinas del sector agroindustrial                     | [principales-exportaciones-argentinas-del-sector-agroindustrial-2](https://argendata.fund.ar/graficos/principales-exportaciones-argentinas-del-sector-agroindustrial-2/)                                     |
| PIB agropecuario sobre el PIB total                                                | [pib-agropecuario-sobre-el-pib-total](https://argendata.fund.ar/graficos/pib-agropecuario-sobre-el-pib-total/)                                                                                               |
| Historia reciente del PIB agropecuario                                             | [historia-reciente-del-pib-agropecuario](https://argendata.fund.ar/graficos/historia-reciente-del-pib-agropecuario/)                                                                                         |
| Importancia de los distintos sectores que componen el PIB agropecuario             | [importancia-de-los-distintos-sectores-que-componen-el-pib-agropecuario](https://argendata.fund.ar/graficos/importancia-de-los-distintos-sectores-que-componen-el-pib-agropecuario/)                         |
| Evolución del agro y la pesca en Argentina y otros países                          | [evolucion-del-agro-y-la-pesca-en-argentina-y-otros-paises](https://argendata.fund.ar/graficos/evolucion-del-agro-y-la-pesca-en-argentina-y-otros-paises/)                                                   |
| Importancia del agro y la pesca en Argentina y otros países                        | [importancia-del-agro-y-la-pesca-en-argentina-y-otros-paises](https://argendata.fund.ar/graficos/importancia-del-agro-y-la-pesca-en-argentina-y-otros-paises/)                                               |
| Participación del agro en las economías provinciales                               | [valor-agregado-bruto-del-sector-agropecuario-por-provincia](https://argendata.fund.ar/graficos/valor-agregado-bruto-del-sector-agropecuario-por-provincia/)                                                 |
| Cultivos principales de Argentina                                                  | [cultivos-principales-de-argentina](https://argendata.fund.ar/graficos/cultivos-principales-de-argentina/)                                                                                                   |
| Producción de maíz, soja y trigo                                                   | [produccion-de-maiz-soja-y-trigo](https://argendata.fund.ar/graficos/produccion-de-maiz-soja-y-trigo/)                                                                                                       |
| Extensión de superficie sembrada de cada cultivo                                   | [extension-de-superficie-sembrada-de-cada-cultivo](https://argendata.fund.ar/graficos/extension-de-superficie-sembrada-de-cada-cultivo/)                                                                     |
| Cantidad de kg que rinde una hectárea de maíz, soja y trigo                        | [cantidad-de-kg-que-rinde-una-hectarea-de-maiz-soja-y-trigo](https://argendata.fund.ar/graficos/cantidad-de-kg-que-rinde-una-hectarea-de-maiz-soja-y-trigo/)                                                 |
| Producción de maíz en los principales países productores                           | [produccion-de-maiz-en-los-principales-paises-productores](https://argendata.fund.ar/graficos/produccion-de-maiz-en-los-principales-paises-productores/)                                                     |
| Producción de soja en los principales países productores                           | [produccion-de-soja-en-los-principales-paises-productores](https://argendata.fund.ar/graficos/produccion-de-soja-en-los-principales-paises-productores/)                                                     |
| Producción de trigo en los principales países productores                          | [produccion-de-trigo-en-los-principales-paises-productores](https://argendata.fund.ar/graficos/produccion-de-trigo-en-los-principales-paises-productores/)                                                   |
| Países con mayor superficie destinada a la agricultura                             | [paises-con-mayor-superficie-destinada-a-la-agricultura](https://argendata.fund.ar/graficos/paises-con-mayor-superficie-destinada-a-la-agricultura/)                                                         |
| Principales países productores de soja                                             | [principales-paises-productores-de-soja](https://argendata.fund.ar/graficos/principales-paises-productores-de-soja/)                                                                                         |
| Principales países productores de maíz                                             | [principales-paises-productores-de-maiz](https://argendata.fund.ar/graficos/principales-paises-productores-de-maiz/)                                                                                         |
| Producción pecuaria por tipo de ganado                                             | [produccion-pecuaria-por-tipo-de-ganado](https://argendata.fund.ar/graficos/produccion-pecuaria-por-tipo-de-ganado/)                                                                                         |
| Consumo de proteínas animales per cápita                                           | [consumo-de-proteinas-animales-per-capita](https://argendata.fund.ar/graficos/consumo-de-proteinas-animales-per-capita/)                                                                                     |
| Consumo de proteínas animales per cápita en países y regiones seleccionados        | [consumo-de-proteinas-animales-per-capita-en-paises-y-regiones-seleccionados](https://argendata.fund.ar/graficos/consumo-de-proteinas-animales-per-capita-en-paises-y-regiones-seleccionados/)               |
| Principales países productores de carne bovina                                     | [principales-paises-productores-de-carne-bovina](https://argendata.fund.ar/graficos/principales-paises-productores-de-carne-bovina/)                                                                         |
| Principales países productores de carne aviar                                      | [principales-paises-productores-de-carne-aviar](https://argendata.fund.ar/graficos/principales-paises-productores-de-carne-aviar/)                                                                           |
| Producción de carne vacuna a nivel global                                          | [produccion-de-carne-bovina-a-nivel-global](https://argendata.fund.ar/graficos/produccion-de-carne-bovina-a-nivel-global/)                                                                                   |
| Exportaciones globales de carne vacuna                                             | [exportaciones-globales-de-carne-bovina](https://argendata.fund.ar/graficos/exportaciones-globales-de-carne-bovina/)                                                                                         |
| Exportaciones de carne vacuna en relación al resto de las exportaciones argentinas | [exportaciones-de-carne-bovina-en-relacion-al-resto-de-las-exportaciones-argentinas](https://argendata.fund.ar/graficos/exportaciones-de-carne-bovina-en-relacion-al-resto-de-las-exportaciones-argentinas/) |
| Regiones productoras de ganado vacuno en Argentina                                 | [regiones-productoras-de-ganado-bovino-en-argentina](https://argendata.fund.ar/graficos/regiones-productoras-de-ganado-bovino-en-argentina/)                                                                 |
| Peso de las cadenas agroindustriales dentro del PIB argentino                      | [peso-de-las-cadenas-agroindustriales-dentro-del-pib-argentino](https://argendata.fund.ar/graficos/peso-de-las-cadenas-agroindustriales-dentro-del-pib-argentino/)                                           |
| Principales cadenas agroindustriales de Argentina                                  | [principales-caa-de-argentina](https://argendata.fund.ar/graficos/principales-caa-de-argentina/)                                                                                                             |
| Valor agregado de las cadenas agroindustriales en las últimas dos décadas          | [valor-agregado-de-las-caa-en-las-ultimas-dos-decadas](https://argendata.fund.ar/graficos/valor-agregado-de-las-caa-en-las-ultimas-dos-decadas/)                                                             |
| Ubicación de las distintas cadenas agroindustriales                                | [ubicacion-de-las-distintas-cadenas-agroindustriales](https://argendata.fund.ar/graficos/ubicacion-de-las-distintas-cadenas-agroindustriales/)                                                               |
| Exportaciones por cadena agroindustrial                                            | [exportaciones-por-caa](https://argendata.fund.ar/graficos/exportaciones-por-caa/)                                                                                                                           |
| Proporción de exportaciones de productos primarios y MOA                           | [proporcion-de-exportaciones-de-productos-primarios-y-moa](https://argendata.fund.ar/graficos/proporcion-de-exportaciones-de-productos-primarios-y-moa/)                                                     |
| Índices de precios de exportación de rubros seleccionados                          | [indices-de-precios-de-exportacion-de-rubros-seleccionados](https://argendata.fund.ar/graficos/indices-de-precios-de-exportacion-de-rubros-seleccionados/)                                                   |
| Principales productos exportados vinculados al sector agroindustrial               | [principales-productos-exportados-vinculados-al-sector-agroindustrial](https://argendata.fund.ar/graficos/principales-productos-exportados-vinculados-al-sector-agroindustrial/)                             |
| Principales exportaciones argentinas del sector agroindustrial                     | [principales-exportaciones-argentinas-del-sector-agroindustrial](https://argendata.fund.ar/graficos/principales-exportaciones-argentinas-del-sector-agroindustrial/)                                         |

## [Cambio climático y emisiones de gases de efecto invernadero](./CAMCLI/)
[(volver al índice)](#índice)

| titulo                                                                                             | link                                                                                                                                                                                   |
|:---------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Anomalía anual de temperatura media a nivel país                                                   | [anomalia-anual-de-temperatura-media-a-nivel-pais](https://argendata.fund.ar/graficos/anomalia-anual-de-temperatura-media-a-nivel-pais/)                                               |
| Cambio en el número de días con heladas en Argentina                                               | [mapa-de-variaciones-de-la-temperatura-en-la-argentina](https://argendata.fund.ar/graficos/mapa-de-variaciones-de-la-temperatura-en-la-argentina/)                                     |
| Cambio en el número de días con ola de calor                                                       | [mapa-de-variaciones-de-la-cantidad-de-dias-de-ola-de-calor-en-argentina](https://argendata.fund.ar/graficos/mapa-de-variaciones-de-la-cantidad-de-dias-de-ola-de-calor-en-argentina/) |
| Impactos y riesgos del cambio climático                                                            | [impactos-y-riesgos-del-cambio-climatico](https://argendata.fund.ar/graficos/impactos-y-riesgos-del-cambio-climatico/)                                                                 |
| Aporte de cada país a las emisiones de CO₂                                                         | [aporte-de-cada-pais-a-las-emisiones-de-co2](https://argendata.fund.ar/graficos/aporte-de-cada-pais-a-las-emisiones-de-co2/)                                                           |
| Emisiones de dióxido de carbono                                                                    | [emisiones-de-dioxido-de-carbono](https://argendata.fund.ar/graficos/emisiones-de-dioxido-de-carbono/)                                                                                 |
| Emisiones de dióxido de carbono per cápita                                                         | [emisiones-de-dioxido-de-carbono-co%e2%82%82-per-capita](https://argendata.fund.ar/graficos/emisiones-de-dioxido-de-carbono-co%e2%82%82-per-capita/)                                   |
| Emisiones de gases de efecto invernadero por sector                                                | [emisiones-de-gases-de-efecto-invernadero-por-sector-2016](https://argendata.fund.ar/graficos/emisiones-de-gases-de-efecto-invernadero-por-sector-2016/)                               |
| Emisiones de gases de efecto invernadero por sector                                                | [emisiones-de-gases-de-efecto-invernadero-por-sector-1850-20143](https://argendata.fund.ar/graficos/emisiones-de-gases-de-efecto-invernadero-por-sector-1850-20143/)                   |
| Emisiones de GEI por sector en Argentina                                                           | [emisiones-de-gei-por-sector-en-argentina-2018](https://argendata.fund.ar/graficos/emisiones-de-gei-por-sector-en-argentina-2018/)                                                     |
| Emisiones de GEI por sector en Argentina y el mundo                                                | [emisiones-de-gei-por-sector-en-argentina-y-el-mundo](https://argendata.fund.ar/graficos/emisiones-de-gei-por-sector-en-argentina-y-el-mundo/)                                         |
| Emisiones de GEI en Argentina                                                                      | [emisiones-de-gei-en-argentina](https://argendata.fund.ar/graficos/emisiones-de-gei-en-argentina/)                                                                                     |
| Emisiones de GEI por sector en Argentina                                                           | [emisiones-de-gei-por-sector-en-argentina-2](https://argendata.fund.ar/graficos/emisiones-de-gei-por-sector-en-argentina-2/)                                                           |
| Emisiones de GEI del sector energía en Argentina                                                   | [emisiones-de-gei-del-sector-energia-en-argentina](https://argendata.fund.ar/graficos/emisiones-de-gei-del-sector-energia-en-argentina/)                                               |
| Emisiones de GEI de la agricultura, ganadería, silvicultura y otros usos de la tierra en Argentina | [emisiones-de-gei-del-sector-agsyout-en-argentina](https://argendata.fund.ar/graficos/emisiones-de-gei-del-sector-agsyout-en-argentina/)                                               |
| Emisiones de GEI de los procesos industriales en Argentina                                         | [emisiones-de-gei-del-sector-piup-en-argentina](https://argendata.fund.ar/graficos/emisiones-de-gei-del-sector-piup-en-argentina/)                                                     |
| Emisiones de GEI del sector residuos en Argentina                                                  | [emisiones-de-gei-del-sector-residuos-en-argentina](https://argendata.fund.ar/graficos/emisiones-de-gei-del-sector-residuos-en-argentina/)                                             |
| Emisiones de GEI por sector en las provincias argentinas                                           | [emisiones-de-gei-por-sector-en-las-provincias-argentinas](https://argendata.fund.ar/graficos/emisiones-de-gei-por-sector-en-las-provincias-argentinas/)                               |
| Emisión de GEI y PIB per cápita                                                                    | [emision-de-gei-y-pbi-per-capita](https://argendata.fund.ar/graficos/emision-de-gei-y-pbi-per-capita/)                                                                                 |
| Composición de las emisiones de GEI                                                                | [presencia-del-co2-en-la-atmosfera](https://argendata.fund.ar/graficos/presencia-del-co2-en-la-atmosfera/)                                                                             |
| Emisiones de gases de efecto invernadero                                                           | [emisiones-globales-de-dioxido-de-carbono-co%e2%82%82](https://argendata.fund.ar/graficos/emisiones-globales-de-dioxido-de-carbono-co%e2%82%82/)                                       |
| Presencia del CO₂ en la atmósfera                                                                  | [presencia-del-co%e2%82%82-en-la-atmosfera](https://argendata.fund.ar/graficos/presencia-del-co%e2%82%82-en-la-atmosfera/)                                                             |
| Aumento de la temperatura                                                                          | [aumento-de-la-temperatura](https://argendata.fund.ar/graficos/aumento-de-la-temperatura/)                                                                                             |
| Anomalías de temperatura en el mar y el continente                                                 | [anomalias-en-la-temperatura-de-la-superficie-del-mar](https://argendata.fund.ar/graficos/anomalias-en-la-temperatura-de-la-superficie-del-mar/)                                       |
| Aumento de la altura del nivel del mar                                                             | [aumento-de-la-altura-del-nivel-del-mar](https://argendata.fund.ar/graficos/aumento-de-la-altura-del-nivel-del-mar/)                                                                   |
| Temperatura media anual: niveles y variaciones                                                     | [mapa-de-variaciones-de-la-temperatura-en-la-argentina-2](https://argendata.fund.ar/graficos/mapa-de-variaciones-de-la-temperatura-en-la-argentina-2/)                                 |
| Mapa de variaciones de la temperatura en la Argentina                                              | [mapa-de-variaciones-de-la-temperatura-en-la-argentina-3](https://argendata.fund.ar/graficos/mapa-de-variaciones-de-la-temperatura-en-la-argentina-3/)                                 |
| Mapas de precipitación media en Argentina                                                          | [mapas-de-precipitacion-media-en-argentina](https://argendata.fund.ar/graficos/mapas-de-precipitacion-media-en-argentina/)                                                             |
| Mapa del cambio de precipitaciones en Argentina                                                    | [mapa-del-cambio-de-precipitaciones-en-argentina](https://argendata.fund.ar/graficos/mapa-del-cambio-de-precipitaciones-en-argentina/)                                                 |
| Mapa de precipitación máxima diaria en Argentina                                                   | [mapa-de-precipitacion-maxima-en-argentina](https://argendata.fund.ar/graficos/mapa-de-precipitacion-maxima-en-argentina/)                                                             |
| Mapa de cambios en las precipitaciones en Argentina                                                | [mapa-de-cambios-en-las-precipitaciones-en-argentina](https://argendata.fund.ar/graficos/mapa-de-cambios-en-las-precipitaciones-en-argentina/)                                         |
| Aumentos y descensos de temperatura en el Mar Argentino                                            | [aumentos-y-descensos-de-temperatura-en-el-mar-argentino](https://argendata.fund.ar/graficos/aumentos-y-descensos-de-temperatura-en-el-mar-argentino/)                                 |

## [Comercio exterior](./COMEXT/)
[(volver al índice)](#índice)

| titulo                                                                                       | link                                                                                                                                                                                                                             |
|:---------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Exportaciones de Argentina en el largo plazo                                                 | [exportaciones-de-argentina-en-el-largo-plazo](https://argendata.fund.ar/graficos/exportaciones-de-argentina-en-el-largo-plazo/)                                                                                                 |
| Valor de las exportaciones de bienes y servicios de Argentina                                | [valor-de-las-exportaciones-de-bienes-y-servicios-de-argentina](https://argendata.fund.ar/graficos/valor-de-las-exportaciones-de-bienes-y-servicios-de-argentina/)                                                               |
| Participación de los servicios en el total de las exportaciones                              | [participacion-de-los-servicios-en-el-total-de-las-exportaciones](https://argendata.fund.ar/graficos/participacion-de-los-servicios-en-el-total-de-las-exportaciones/)                                                           |
| Participación de las exportaciones de bienes y servicios en el PIB                           | [participacion-de-las-exportaciones-de-bienes-y-servicios](https://argendata.fund.ar/graficos/participacion-de-las-exportaciones-de-bienes-y-servicios/)                                                                         |
| Participación de las exportaciones de bienes y servicios de Argentina en el comercio mundial | [participacion-de-las-exportaciones-de-bienes-y-servicios-de-argentina-en-el-comercio-mundial](https://argendata.fund.ar/graficos/participacion-de-las-exportaciones-de-bienes-y-servicios-de-argentina-en-el-comercio-mundial/) |
| Participación en el comercio mundial de Argentina y otros países de América Latina           | [participacion-en-el-comercio-mundial-de-argentina-y-otros-paises-de-america-latina](https://argendata.fund.ar/graficos/participacion-en-el-comercio-mundial-de-argentina-y-otros-paises-de-america-latina/)                     |
| Precios de exportación en Argentina y otros países de América Latina                         | [precios-de-exportacion-en-argentina-y-otros-paises-de-america-latina](https://argendata.fund.ar/graficos/precios-de-exportacion-en-argentina-y-otros-paises-de-america-latina/)                                                 |
| Volumen de las exportaciones de bienes para Argentina y otros países de América Latina       | [volumen-de-las-exportaciones-de-bienes-para-argentina-y-otros-paises-de-america-latina](https://argendata.fund.ar/graficos/volumen-de-las-exportaciones-de-bienes-para-argentina-y-otros-paises-de-america-latina/)             |
| Apertura comercial de Argentina y otros países de América Latina                             | [apertura-comercial-de-argentina-y-otros-paises-de-america-latina](https://argendata.fund.ar/graficos/apertura-comercial-de-argentina-y-otros-paises-de-america-latina/)                                                         |
| Composición de las exportaciones argentinas de bienes                                        | [composicion-de-las-exportaciones-argentinas-de-bienes](https://argendata.fund.ar/graficos/composicion-de-las-exportaciones-argentinas-de-bienes/)                                                                               |
| Importaciones argentinas de bienes                                                           | [importaciones-argentinas-de-bienes](https://argendata.fund.ar/graficos/importaciones-argentinas-de-bienes/)                                                                                                                     |
| Exportaciones de Argentina                                                                   | [exportaciones-e-importaciones-de-argentina](https://argendata.fund.ar/graficos/exportaciones-e-importaciones-de-argentina/)                                                                                                     |
| Importaciones de Argentina                                                                   | [exportaciones-e-importaciones-de-argentina-2](https://argendata.fund.ar/graficos/exportaciones-e-importaciones-de-argentina-2/)                                                                                                 |
| Exportaciones según grado de diferenciación del productos                                    | [exportaciones-e-importaciones-segun-grado-de-diferenciacion-del-productos](https://argendata.fund.ar/graficos/exportaciones-e-importaciones-segun-grado-de-diferenciacion-del-productos/)                                       |
| Importaciones según grado de diferenciación del productos                                    | [exportaciones-e-importaciones-segun-grado-de-diferenciacion-del-productos-2](https://argendata.fund.ar/graficos/exportaciones-e-importaciones-segun-grado-de-diferenciacion-del-productos-2/)                                   |
| Destinos de las exportaciones argentinas                                                     | [destinos-de-las-exportaciones-argentinas](https://argendata.fund.ar/graficos/destinos-de-las-exportaciones-argentinas/)                                                                                                         |
| Origen de las importaciones argentinas                                                       | [origen-de-las-importaciones-argentinas](https://argendata.fund.ar/graficos/origen-de-las-importaciones-argentinas/)                                                                                                             |
| Cambio en los destinos de exportación                                                        | [cambio-en-los-destinos-de-exportacion](https://argendata.fund.ar/graficos/cambio-en-los-destinos-de-exportacion/)                                                                                                               |
| Cambio en los orígenes de importación                                                        | [cambio-en-los-origenes-de-importacion](https://argendata.fund.ar/graficos/cambio-en-los-origenes-de-importacion/)                                                                                                               |
| Composición de las exportaciones argentinas de servicios                                     | [composicion-de-las-exportaciones-argentinas-de-servicios](https://argendata.fund.ar/graficos/composicion-de-las-exportaciones-argentinas-de-servicios/)                                                                         |
| Top 20 países de destino de las exportaciones argentinas de servicios                        | [top-20-paises-de-destino-de-las-exportaciones-argentinas-de-servicios](https://argendata.fund.ar/graficos/top-20-paises-de-destino-de-las-exportaciones-argentinas-de-servicios/)                                               |

## [Crecimiento](./CRECIM/)
[(volver al índice)](#índice)

| titulo                                                                                                | link                                                                                                                                                                                                                       |
|:------------------------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Primeros diez países según PIB y PIB per cápita                                                       | [primeros-diez-paises-segun-pib-y-pib-per-capita](https://argendata.fund.ar/graficos/primeros-diez-paises-segun-pib-y-pib-per-capita/)                                                                                     |
| PIB per cápita y expectativa de vida al nacer                                                         | [pib-per-capita-y-expectativa-de-vida-al-nacer](https://argendata.fund.ar/graficos/pib-per-capita-y-expectativa-de-vida-al-nacer/)                                                                                         |
| PIB per cápita y promedio de años de escolarización                                                   | [pib-per-capita-y-promedio-de-anos-de-escolarizacion](https://argendata.fund.ar/graficos/pib-per-capita-y-promedio-de-anos-de-escolarizacion/)                                                                             |
| PIB per cápita e ingreso/consumo promedio                                                             | [pib-per-capita-e-ingreso-consumo-promedio](https://argendata.fund.ar/graficos/pib-per-capita-e-ingreso-consumo-promedio/)                                                                                                 |
| PIB corriente y constante de Argentina                                                                | [pib-corriente-y-constante-de-argentina](https://argendata.fund.ar/graficos/pib-corriente-y-constante-de-argentina/)                                                                                                       |
| PIB per cápita de países seleccionados                                                                | [pib-per-capita-de-paises-seleccionados](https://argendata.fund.ar/graficos/pib-per-capita-de-paises-seleccionados/)                                                                                                       |
| Participación de Argentina en el PIB mundial                                                          | [participacion-de-argentina-en-el-pib-mundial](https://argendata.fund.ar/graficos/participacion-de-argentina-en-el-pib-mundial/)                                                                                           |
| Cambio en el PIB per cápita en la historia reciente                                                   | [cambio-en-el-pib-per-capita-en-la-historia-reciente](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-en-la-historia-reciente/)                                                                             |
| PIB per cápita de Argentina y otros países                                                            | [pib-per-capita-de-argentina-y-otros-paises](https://argendata.fund.ar/graficos/pib-per-capita-de-argentina-y-otros-paises/)                                                                                               |
| Participación de Argentina, Brasil y México en el PIB de América Latina                               | [participacion-de-argentina-brasil-y-mexico-en-el-pib-de-america-latina](https://argendata.fund.ar/graficos/participacion-de-argentina-brasil-y-mexico-en-el-pib-de-america-latina/)                                       |
| Cambio en el PIB per cápita de Argentina y la región                                                  | [cambio-en-el-pib-per-capita-de-argentina-y-la-region](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-de-argentina-y-la-region/)                                                                           |
| Producto interno bruto (PIB) por provincia y región                                                   | [valor-agregado-bruto-vab-por-provincia-y-region](https://argendata.fund.ar/graficos/valor-agregado-bruto-vab-por-provincia-y-region/)                                                                                     |
| Valor Agregado Bruto (VAB) per cápita por provincia                                                   | [vab-per-capita-por-provincia](https://argendata.fund.ar/graficos/vab-per-capita-por-provincia/)                                                                                                                           |
| Participación de las regiones en el PIB argentino                                                     | [participacion-las-regiones-en-el-pib-argentino](https://argendata.fund.ar/graficos/participacion-las-regiones-en-el-pib-argentino/)                                                                                       |
| Variación en la participación en el PIB total                                                         | [variacion-en-la-participacion-en-el-pib-total](https://argendata.fund.ar/graficos/variacion-en-la-participacion-en-el-pib-total/)                                                                                         |
| Correlación entre el nivel del PIB per cápita provincial y la variación del PIB per cápita provincial | [correlacion-entre-el-pib-per-capita-provincial-y-la-variacion-del-pib-per-capita-nacional](https://argendata.fund.ar/graficos/correlacion-entre-el-pib-per-capita-provincial-y-la-variacion-del-pib-per-capita-nacional/) |
| PIB per cápita de Buenos Aires, CABA, Córdoba, Mendoza y Santa Fe                                     | [pib-per-capita-de-buenos-aires-caba-cordoba-mendoza-santa-fe-y-total](https://argendata.fund.ar/graficos/pib-per-capita-de-buenos-aires-caba-cordoba-mendoza-santa-fe-y-total/)                                           |
| VAB de cada provincia                                                                                 | [vab-de-cada-provincia](https://argendata.fund.ar/graficos/vab-de-cada-provincia/)                                                                                                                                         |
| PIB per cápita provincial en relación a la media nacional                                             | [pib-per-capita-segun-la-media-nacional](https://argendata.fund.ar/graficos/pib-per-capita-segun-la-media-nacional/)                                                                                                       |
| Cambio en el PIB per cápita en el mundo                                                               | [cambio-en-el-pib-per-capita-en-el-mundo](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-en-el-mundo/)                                                                                                     |
| Cambio en el PIB per cápita en el siglo XIX                                                           | [cambio-en-el-pib-per-capita-en-el-siglo-xix](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-en-el-siglo-xix/)                                                                                             |
| Cambio en el PIB per cápita en Argentina                                                              | [cambio-en-el-pib-per-capita-en-argentina](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-en-argentina/)                                                                                                   |
| PIB per cápita (escala logarítmica)                                                                   | [cambio-en-el-pib-per-capita-de-paises-seleccionados-en-escala-logaritmica](https://argendata.fund.ar/graficos/cambio-en-el-pib-per-capita-de-paises-seleccionados-en-escala-logaritmica/)                                 |
| Cambio en el PIB per cápita en Argentina                                                              | [historia-del-cambio-en-el-pib-per-capita-en-argentina](https://argendata.fund.ar/graficos/historia-del-cambio-en-el-pib-per-capita-en-argentina/)                                                                         |
| PIB per cápita de Argentina en relación al de otros países latinoamericanos                           | [pib-per-capita-de-argentina-como-porcentaje-del-de-otros-paises-latinoamericanos](https://argendata.fund.ar/graficos/pib-per-capita-de-argentina-como-porcentaje-del-de-otros-paises-latinoamericanos/)                   |

## [Desarrollo humano](./DESHUM/)
[(volver al índice)](#índice)

| titulo                                                                                                       | link                                                                                                                                                                                             |
|:-------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Índice de Desarrollo Humano en el mundo                                                                      | [indice-de-desarrollo-humano-en-el-mundo](https://argendata.fund.ar/graficos/indice-de-desarrollo-humano-en-el-mundo/)                                                                           |
| Índice de Desarrollo Humano en Argentina                                                                     | [indice-de-desarrollo-humano-en-argentina](https://argendata.fund.ar/graficos/indice-de-desarrollo-humano-en-argentina/)                                                                         |
| Índice de Desarrollo Humano en regiones y países seleccionados                                               | [indice-de-desarrollo-humano-en-paises-seleccionados](https://argendata.fund.ar/graficos/indice-de-desarrollo-humano-en-paises-seleccionados/)                                                   |
| Expectativa de vida al nacer en países seleccionados                                                         | [expectativa-de-vida-al-nacer-en-paises-seleccionados](https://argendata.fund.ar/graficos/expectativa-de-vida-al-nacer-en-paises-seleccionados/)                                                 |
| Ingreso Nacional Bruto (INB) per cápita en países seleccionados                                              | [ingreso-nacional-bruto-inb-per-capita-en-paises-seleccionados](https://argendata.fund.ar/graficos/ingreso-nacional-bruto-inb-per-capita-en-paises-seleccionados/)                               |
| Años de educación en países seleccionados                                                                    | [anos-de-educacion-en-paises-seleccionados](https://argendata.fund.ar/graficos/anos-de-educacion-en-paises-seleccionados/)                                                                       |
| Años de educación esperados en países seleccionados                                                          | [anos-de-educacion-esperados-en-paises-seleccionados](https://argendata.fund.ar/graficos/anos-de-educacion-esperados-en-paises-seleccionados/)                                                   |
| Índice de Desarrollo Humano por subcomponente                                                                | [idh-por-subcomponentes](https://argendata.fund.ar/graficos/idh-por-subcomponentes/)                                                                                                             |
| Índice de Desarrollo Humano e Índice de Desarrollo Humano ajustado por Desigualdad para países seleccionados | [idh-e-idh-ajustado-por-desigualdad-idh-d-para-paises-seleccionados](https://argendata.fund.ar/graficos/idh-e-idh-ajustado-por-desigualdad-idh-d-para-paises-seleccionados/)                     |
| Índice de Desarrollo Humano ajustado por Desigualdad para países y regiones seleccionadas                    | [idh-d-para-paises-y-regiones-seleccionadas](https://argendata.fund.ar/graficos/idh-d-para-paises-y-regiones-seleccionadas/)                                                                     |
| Índice de Desarrollo de Género en Argentina y el mundo                                                       | [indice-de-desarrollo-de-genero-para-argentina-y-el-mundo](https://argendata.fund.ar/graficos/indice-de-desarrollo-de-genero-para-argentina-y-el-mundo/)                                         |
| Índice de Desarrollo Humano según género para países seleccionados                                           | [idh-segun-genero-para-paises-seleccionados](https://argendata.fund.ar/graficos/idh-segun-genero-para-paises-seleccionados/)                                                                     |
| Índice de Desarrollo Humano y penalidad por presiones planetarias                                            | [idh-y-penalidad-por-presiones-planetarias](https://argendata.fund.ar/graficos/idh-y-penalidad-por-presiones-planetarias/)                                                                       |
| Ranking de Índice de Desarrollo Humano e Índice de Desarrollo Humano ajustado por presiones planetarias      | [ranking-de-idh-comun-e-idh-ajustado-por-presiones-planetarias](https://argendata.fund.ar/graficos/ranking-de-idh-comun-e-idh-ajustado-por-presiones-planetarias/)                               |
| IDH e IDH ajustado por presiones planetarias para Argentina                                                  | [idh-e-idh-ajustado-por-presiones-planetarias-para-argentina](https://argendata.fund.ar/graficos/idh-e-idh-ajustado-por-presiones-planetarias-para-argentina/)                                   |
| Índice de Desarrollo Humano aumentado de Argentina                                                           | [idh-aumentado-de-argentina](https://argendata.fund.ar/graficos/idh-aumentado-de-argentina/)                                                                                                     |
| Índice de Desarrollo Humano aumentado para Argentina, Europa Occidental y Ramificaciones de Occidente        | [idh-aumentado-para-argentina-europa-occidental-y-ramificaciones-de-occidente](https://argendata.fund.ar/graficos/idh-aumentado-para-argentina-europa-occidental-y-ramificaciones-de-occidente/) |
| Índice de Desarrollo Humano aumentado para países de América Latina seleccionados                            | [idh-aumentado-para-paises-de-america-latina-seleccionados](https://argendata.fund.ar/graficos/idh-aumentado-para-paises-de-america-latina-seleccionados/)                                       |
| Índice de Desarrollo Humano aumentado para países y regiones seleccionadas                                   | [idh-aumentado-para-paises-y-regiones-seleccionadas](https://argendata.fund.ar/graficos/idh-aumentado-para-paises-y-regiones-seleccionadas/)                                                     |

## [Desigualdad](./DESIGU/)
[(volver al índice)](#índice)

| titulo                                                          | link                                                                                                                                                                   |
|:----------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Desigualdad de ingresos por decil                               | [desigualdad-de-ingresos-por-decil](https://argendata.fund.ar/graficos/desigualdad-de-ingresos-por-decil/)                                                             |
| Desigualdad de ingresos en Argentina según el índice de Gini    | [desigualdad-de-ingresos-segun-el-indice-de-gini](https://argendata.fund.ar/graficos/desigualdad-de-ingresos-segun-el-indice-de-gini/)                                 |
| Brecha de ingresos en Argentina                                 | [brecha-de-ingresos](https://argendata.fund.ar/graficos/brecha-de-ingresos/)                                                                                           |
| La desigualdad en el mundo                                      | [la-desigualdad-en-el-mundo](https://argendata.fund.ar/graficos/la-desigualdad-en-el-mundo/)                                                                           |
| Exceso de desigualdad en Argentina y América Latina             | [exceso-de-desigualdad-en-argentina-y-america-latina](https://argendata.fund.ar/graficos/exceso-de-desigualdad-en-argentina-y-america-latina/)                         |
| Desigualdad de ingresos en Argentina y América Latina           | [desigualdad-de-ingresos-en-argentina-y-america-latina](https://argendata.fund.ar/graficos/desigualdad-de-ingresos-en-argentina-y-america-latina/)                     |
| La movilidad intergeneracional educativa en Argentina           | [la-movilidad-intergeneracional-educativa-en-argentina](https://argendata.fund.ar/graficos/la-movilidad-intergeneracional-educativa-en-argentina/)                     |
| Movilidad intergeneracional educativa en el mundo               | [movilidad-intergeneracional-educativa-en-el-mundo](https://argendata.fund.ar/graficos/movilidad-intergeneracional-educativa-en-el-mundo/)                             |
| Desigualdad de los ingresos laborales y del ingreso per cápita  | [desigualdad-de-los-ingresos-laborales-y-del-ingreso-per-capita](https://argendata.fund.ar/graficos/desigualdad-de-los-ingresos-laborales-y-del-ingreso-per-capita/)   |
| Brecha salarial entre trabajadores calificados y no calificados | [brecha-salarial-entre-trabajadores-calificados-y-no-calificados](https://argendata.fund.ar/graficos/brecha-salarial-entre-trabajadores-calificados-y-no-calificados/) |
| Brecha en tasas de empleo y horas trabajadas                    | [tasas-de-empleo-y-horas-trabajadas](https://argendata.fund.ar/graficos/tasas-de-empleo-y-horas-trabajadas/)                                                           |
| Ingresos laborales y educación                                  | [ingresos-laborales-y-educacion](https://argendata.fund.ar/graficos/ingresos-laborales-y-educacion/)                                                                   |
| Años de educación según ingresos                                | [anos-de-educacion-segun-los-ingresos](https://argendata.fund.ar/graficos/anos-de-educacion-segun-los-ingresos/)                                                       |
| Igualdad de oportunidades educativas                            | [igualdad-de-oportunidades-educativas](https://argendata.fund.ar/graficos/igualdad-de-oportunidades-educativas/)                                                       |
| Distribución funcional del ingreso                              | [distribucion-funcional-del-ingreso](https://argendata.fund.ar/graficos/distribucion-funcional-del-ingreso/)                                                           |
| Desigualdad de ingresos en Argentina                            | [desigualdad-de-ingresos-en-argentina](https://argendata.fund.ar/graficos/desigualdad-de-ingresos-en-argentina/)                                                       |
| Desigualdad de ingresos por regiones                            | [desigualdad-de-ingresos-por-regiones](https://argendata.fund.ar/graficos/desigualdad-de-ingresos-por-regiones/)                                                       |
| Brechas regionales de ingreso                                   | [brechas-regionales-de-ingreso](https://argendata.fund.ar/graficos/brechas-regionales-de-ingreso/)                                                                     |
| Cantidad de niños por hogar                                     | [cantidad-de-ninos-por-hogar](https://argendata.fund.ar/graficos/cantidad-de-ninos-por-hogar/)                                                                         |
| Grado de emparejamiento selectivo                               | [grado-de-emparejamiento-selectivo](https://argendata.fund.ar/graficos/grado-de-emparejamiento-selectivo/)                                                             |
| Brecha de género en el ingreso laboral horario                  | [brecha-de-genero-en-el-ingreso-laboral-horario](https://argendata.fund.ar/graficos/brecha-de-genero-en-el-ingreso-laboral-horario/)                                   |
| Tasas de participación laboral en Argentina                     | [tasas-de-participacion-laboral](https://argendata.fund.ar/graficos/tasas-de-participacion-laboral/)                                                                   |
| Propiedad de la vivienda                                        | [propiedad-de-la-vivienda](https://argendata.fund.ar/graficos/propiedad-de-la-vivienda/)                                                                               |
| Brecha en el acceso a servicios                                 | [brecha-en-el-acceso-a-servicios](https://argendata.fund.ar/graficos/brecha-en-el-acceso-a-servicios/)                                                                 |
| Cantidad de horas trabajadas remuneradas                        | [cantidad-de-horas-trabajadas-remuneradas](https://argendata.fund.ar/graficos/cantidad-de-horas-trabajadas-remuneradas/)                                               |

## [Estructura productiva](./ESTPRO/)
[(volver al índice)](#índice)

| titulo                                                                                   | link                                                                                                                                                                                                                                                                                                                                                                       |
|:-----------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Peso de los diferentes sectores en la estructura productiva argentina                    | [peso-de-los-diferentes-sectores-de-la-estructura-productiva-argentina](https://argendata.fund.ar/graficos/peso-de-los-diferentes-sectores-de-la-estructura-productiva-argentina/)                                                                                                                                                                                         |
| PIB según sectores                                                                       | [pib-segun-sectores](https://argendata.fund.ar/graficos/pib-segun-sectores/)                                                                                                                                                                                                                                                                                               |
| Peso de los servicios en las economías de países seleccionados                           | [peso-de-los-servicios-en-las-economias-de-paises-seleccionados](https://argendata.fund.ar/graficos/peso-de-los-servicios-en-las-economias-de-paises-seleccionados/)                                                                                                                                                                                                       |
| Peso de los distintos sectores productivos en países seleccionados                       | [peso-de-los-distintos-sectores-productivos-en-paises-seleccionados](https://argendata.fund.ar/graficos/peso-de-los-distintos-sectores-productivos-en-paises-seleccionados/)                                                                                                                                                                                               |
| Bienes y servicios intensivos en I+D en países seleccionados                             | [bienes-y-servicios-intensivos-en-id-en-paises-seleccionados](https://argendata.fund.ar/graficos/bienes-y-servicios-intensivos-en-id-en-paises-seleccionados/)                                                                                                                                                                                                             |
| Estructura sectorial del empleo                                                          | [estructura-sectorial-del-empleo](https://argendata.fund.ar/graficos/estructura-sectorial-del-empleo/)                                                                                                                                                                                                                                                                     |
| Participación de los sectores en el empleo versus su participación en el PIB             | [participacion-de-los-sectores-en-el-empleo-versus-su-participacion-en-el-pib](https://argendata.fund.ar/graficos/participacion-de-los-sectores-en-el-empleo-versus-su-participacion-en-el-pib/)                                                                                                                                                                           |
| Estructura sectorial del empleo en Argentina                                             | [estructura-sectorial-del-empleo-en-argentina](https://argendata.fund.ar/graficos/estructura-sectorial-del-empleo-en-argentina/)                                                                                                                                                                                                                                           |
| Nivel de calificación del empleo por sector                                              | [nivel-de-calificacion-del-empleo-por-sectornivel-de-calificacion-del-empleo-en-argentina-en-porcentaje-por-sector-2023nivel-de-calificacion-del-empleo-por-sector](https://argendata.fund.ar/graficos/nivel-de-calificacion-del-empleo-por-sectornivel-de-calificacion-del-empleo-en-argentina-en-porcentaje-por-sector-2023nivel-de-calificacion-del-empleo-por-sector/) |
| Composición por género de cada sector                                                    | [composicion-por-genero-de-cada-sector](https://argendata.fund.ar/graficos/composicion-por-genero-de-cada-sector/)                                                                                                                                                                                                                                                         |
| Tasa de feminización                                                                     | [tasa-de-feminizacion](https://argendata.fund.ar/graficos/tasa-de-feminizacion/)                                                                                                                                                                                                                                                                                           |
| PIB sectorial por región                                                                 | [vab-sectorial-por-region](https://argendata.fund.ar/graficos/vab-sectorial-por-region/)                                                                                                                                                                                                                                                                                   |
| Estructura productiva en cada provincia                                                  | [estructura-productiva-en-cada-provincia](https://argendata.fund.ar/graficos/estructura-productiva-en-cada-provincia/)                                                                                                                                                                                                                                                     |
| PIB por ocupado en países seleccionados                                                  | [pib-por-ocupado-en-paises-seleccionados](https://argendata.fund.ar/graficos/pib-por-ocupado-en-paises-seleccionados/)                                                                                                                                                                                                                                                     |
| Productividad en distintos países                                                        | [productividad-en-distintos-paises](https://argendata.fund.ar/graficos/productividad-en-distintos-paises/)                                                                                                                                                                                                                                                                 |
| PIB por puesto de trabajo en distintos sectores                                          | [pib-por-puesto-de-trabajo-en-distintos-sectores](https://argendata.fund.ar/graficos/pib-por-puesto-de-trabajo-en-distintos-sectores/)                                                                                                                                                                                                                                     |
| Productividad sectorial de países de la OCDE respecto a Argentina                        | [productividad-sectorial-de-paises-de-la-ocde-respecto-a-argentina](https://argendata.fund.ar/graficos/productividad-sectorial-de-paises-de-la-ocde-respecto-a-argentina/)                                                                                                                                                                                                 |
| Cantidad de empresas en Argentina                                                        | [cantidad-de-empresas-en-argentina](https://argendata.fund.ar/graficos/cantidad-de-empresas-en-argentina/)                                                                                                                                                                                                                                                                 |
| Trabajadores registrados promedio del sector privado por empresa                         | [trabajadores-registrados-promedio-del-sector-privado-por-empresa](https://argendata.fund.ar/graficos/trabajadores-registrados-promedio-del-sector-privado-por-empresa/)                                                                                                                                                                                                   |
| Escala promedio y salarios relativos por rama                                            | [escala-promedio-y-salarios-relativos-por-rama](https://argendata.fund.ar/graficos/escala-promedio-y-salarios-relativos-por-rama/)                                                                                                                                                                                                                                         |
| Densidad empresarial                                                                     | [densidad-empresarial](https://argendata.fund.ar/graficos/densidad-empresarial/)                                                                                                                                                                                                                                                                                           |
| Informalidad asalariada según tamaño del establecimiento                                 | [informalidad-asalariada-segun-tamano-del-establecimiento](https://argendata.fund.ar/graficos/informalidad-asalariada-segun-tamano-del-establecimiento/)                                                                                                                                                                                                                   |
| Densidad empresarial y proporción de población con necesidades básicas insatisfechas     | [densidad-empresarial-y-proporcion-de-poblacion-con-necesidades-basicas-insatisfechas](https://argendata.fund.ar/graficos/densidad-empresarial-y-proporcion-de-poblacion-con-necesidades-basicas-insatisfechas/)                                                                                                                                                           |
| Peso de los bienes y servicios de media y alta intensidad en I+D en países seleccionados | [peso-de-los-bienes-y-servicios-de-media-y-alta-intensidad-en-id-en-paises-seleccionados](https://argendata.fund.ar/graficos/peso-de-los-bienes-y-servicios-de-media-y-alta-intensidad-en-id-en-paises-seleccionados/)                                                                                                                                                     |

## [Informalidad y desempleo](./INFDES/)
[(volver al índice)](#índice)

| titulo                                                         | link                                                                                                                                                                 |
|:---------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Informalidad en América Latina                                 | [informalidad-en-america-latina](https://argendata.fund.ar/graficos/informalidad-en-america-latina/)                                                                 |
| PIB per cápita y formalidad en América Latina                  | [pib-per-capita-y-formalidad-en-america-latina](https://argendata.fund.ar/graficos/pib-per-capita-y-formalidad-en-america-latina/)                                   |
| Empleo según categorías ocupacionales en América Latina        | [empleo-segun-categorias-ocupacionales-en-america-latina](https://argendata.fund.ar/graficos/empleo-segun-categorias-ocupacionales-en-america-latina/)               |
| Informalidad en Argentina según tipo de definición             | [informalidad-en-argentina-segun-tipo-de-definicion](https://argendata.fund.ar/graficos/informalidad-en-argentina-segun-tipo-de-definicion/)                         |
| Informalidad asalariada en América Latina                      | [informalidad-asalariada-en-america-latina](https://argendata.fund.ar/graficos/informalidad-asalariada-en-america-latina/)                                           |
| Informalidad por provincia                                     | [informalidad-por-provincia](https://argendata.fund.ar/graficos/informalidad-por-provincia/)                                                                         |
| Informalidad asalariada por edad y género                      | [informalidad-asalariada-por-edad-y-genero](https://argendata.fund.ar/graficos/informalidad-asalariada-por-edad-y-genero/)                                           |
| Informalidad asalariada por género                             | [informalidad-asalariada-por-genero](https://argendata.fund.ar/graficos/informalidad-asalariada-por-genero/)                                                         |
| Brechas de género en la informalidad en América Latina         | [brechas-de-genero-en-la-informalidad-en-america-latina](https://argendata.fund.ar/graficos/brechas-de-genero-en-la-informalidad-en-america-latina/)                 |
| Tasa de desocupación                                           | [tasa-de-desocupacion](https://argendata.fund.ar/graficos/tasa-de-desocupacion/)                                                                                     |
| Tasa de desocupación en el mundo                               | [tasa-de-desocupacion-en-el-mundo](https://argendata.fund.ar/graficos/tasa-de-desocupacion-en-el-mundo/)                                                             |
| Satisfacción con la vida entre personas ocupadas y desocupadas | [satisfaccion-con-la-vida-entre-personas-ocupadas-y-desocupadas](https://argendata.fund.ar/graficos/satisfaccion-con-la-vida-entre-personas-ocupadas-y-desocupadas/) |
| Desocupación según edad y género                               | [desocupacion-segun-edad-y-genero](https://argendata.fund.ar/graficos/desocupacion-segun-edad-y-genero/)                                                             |
| Desocupación según nivel educativo                             | [desocupacion-segun-nivel-educativo](https://argendata.fund.ar/graficos/desocupacion-segun-nivel-educativo/)                                                         |

## [Trabajo y participación laboral](./MERTRA/)
[(volver al índice)](#índice)

| titulo                                                                                             | link                                                                                                                                                                                                                                                                                                                                 |
|:---------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Participación laboral por género                                                                   | [participacion-laboral-por-genero](https://argendata.fund.ar/graficos/participacion-laboral-por-genero/)                                                                                                                                                                                                                             |
| Participación de mujeres en la fuerza laboral en América Latina                                    | [participacion-de-mujeres-en-la-fuerza-laboral-en-america-latina](https://argendata.fund.ar/graficos/participacion-de-mujeres-en-la-fuerza-laboral-en-america-latina/)                                                                                                                                                               |
| Participación laboral en Argentina y otros países                                                  | [participacion-laboral-en-argentina-y-otros-paises](https://argendata.fund.ar/graficos/participacion-laboral-en-argentina-y-otros-paises/)                                                                                                                                                                                           |
| Actividad según edad                                                                               | [actividad-segun-edad](https://argendata.fund.ar/graficos/actividad-segun-edad/)                                                                                                                                                                                                                                                     |
| Actividad por género y edad                                                                        | [actividad-por-genero-y-edad](https://argendata.fund.ar/graficos/actividad-por-genero-y-edad/)                                                                                                                                                                                                                                       |
| Actividad por edad y región                                                                        | [actividad-por-edad-y-region](https://argendata.fund.ar/graficos/actividad-por-edad-y-region/)                                                                                                                                                                                                                                       |
| Relación entre puestos de trabajo y crecimiento poblacional                                        | [relacion-entre-puestos-de-trabajo-y-crecimiento-poblacional](https://argendata.fund.ar/graficos/relacion-entre-puestos-de-trabajo-y-crecimiento-poblacional/)                                                                                                                                                                       |
| Empleo por provincia                                                                               | [empleo-por-provincia](https://argendata.fund.ar/graficos/empleo-por-provincia/)                                                                                                                                                                                                                                                     |
| Tasa de empleo en adultos y tasa de empleo total por provincia                                     | [empleo-en-adultos-y-tasa-de-empleo-total-por-provincia](https://argendata.fund.ar/graficos/empleo-en-adultos-y-tasa-de-empleo-total-por-provincia/)                                                                                                                                                                                 |
| Empleo por género y provincia                                                                      | [empleo-por-genero-y-provincia](https://argendata.fund.ar/graficos/empleo-por-genero-y-provincia/)                                                                                                                                                                                                                                   |
| Población provincial menor de 18 años y tasa de empleo provincial                                  | [poblacion-provincial-menor-de-18-anos-y-tasa-de-empleo-provincial](https://argendata.fund.ar/graficos/poblacion-provincial-menor-de-18-anos-y-tasa-de-empleo-provincial/)                                                                                                                                                           |
| Establecimientos productivos cada 1.000 habitantes y tasa de empleo                                | [establecimientos-productivos-cada-1000-habitantes-y-tasa-de-empleo](https://argendata.fund.ar/graficos/establecimientos-productivos-cada-1000-habitantes-y-tasa-de-empleo/)                                                                                                                                                         |
| Ingresos laborales y tasa de empleo femenina por provincia                                         | [ingresos-laborales-y-tasa-de-empleo-femenina-por-provincia](https://argendata.fund.ar/graficos/ingresos-laborales-y-tasa-de-empleo-femenina-por-provincia/)                                                                                                                                                                         |
| Hogares que tienen lavarropas automático y tasa de empleo femenina por provincia                   | [hogares-que-tienen-lavarropas-automatico-y-tasa-de-empleo-femenina-por-provincia](https://argendata.fund.ar/graficos/hogares-que-tienen-lavarropas-automatico-y-tasa-de-empleo-femenina-por-provincia/)                                                                                                                             |
| “Cuando escasean los empleos, los varones deberían tener mayor derecho a trabajar que las mujeres” | [poblacion-de-acuerdo-o-desacuerdo-con-la-frase-cuando-escasean-los-empleos-los-varones-deberian-tener-mayor-derecho-a-trabajar-que-las-mujeres](https://argendata.fund.ar/graficos/poblacion-de-acuerdo-o-desacuerdo-con-la-frase-cuando-escasean-los-empleos-los-varones-deberian-tener-mayor-derecho-a-trabajar-que-las-mujeres/) |
| Empleo en población según nivel educativo y provincia                                              | [empleo-en-poblacion-segun-nivel-educativo-y-provincia](https://argendata.fund.ar/graficos/empleo-en-poblacion-segun-nivel-educativo-y-provincia/)                                                                                                                                                                                   |
| Tiempo dedicado al trabajo por sexo                                                                | [tiempo-dedicado-al-trabajo-por-sexo](https://argendata.fund.ar/graficos/tiempo-dedicado-al-trabajo-por-sexo/)                                                                                                                                                                                                                       |
| Tiempo dedicado al trabajo no remunerado por sexo y grupo de edad                                  | [tiempo-dedicado-al-trabajo-no-remunerado-por-sexo-y-grupo-de-edad](https://argendata.fund.ar/graficos/tiempo-dedicado-al-trabajo-no-remunerado-por-sexo-y-grupo-de-edad/)                                                                                                                                                           |
| Tiempo dedicado al trabajo no remunerado por sexo y nivel educativo                                | [tiempo-dedicado-al-trabajo-no-remunerado-por-sexo-y-nivel-educativo](https://argendata.fund.ar/graficos/tiempo-dedicado-al-trabajo-no-remunerado-por-sexo-y-nivel-educativo/)                                                                                                                                                       |
| Tiempo dedicado a trabajos no remunerados por sexo                                                 | [tiempo-dedicado-a-trabajos-no-remunerados-por-sexo](https://argendata.fund.ar/graficos/tiempo-dedicado-a-trabajos-no-remunerados-por-sexo/)                                                                                                                                                                                         |
| Tiempo dedicado al trabajo no remunerado realizado por mujeres para países seleccionados           | [tiempo-dedicado-al-trabajo-no-remunerado-realizado-por-mujeres-para-paises-seleccionados](https://argendata.fund.ar/graficos/tiempo-dedicado-al-trabajo-no-remunerado-realizado-por-mujeres-para-paises-seleccionados/)                                                                                                             |

## [Minería](./MINERI/)
[(volver al índice)](#índice)

| titulo                                                                                                  | link                                                                                                                                                                                                                                                   |
|:--------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Participación de la minería en el PIB                                                                   | [estadisticas-de-la-participacion-de-la-mineria-en-el-pib](https://argendata.fund.ar/graficos/estadisticas-de-la-participacion-de-la-mineria-en-el-pib/)                                                                                               |
| Participación en la producción mundial de los principales países productores de minerales seleccionados | [participacion-en-la-produccion-mundial-de-los-principales-paises-productores-de-minerales-seleccionados](https://argendata.fund.ar/graficos/participacion-en-la-produccion-mundial-de-los-principales-paises-productores-de-minerales-seleccionados/) |
| Participación de las exportaciones mineras por rubro en el total de las exportaciones                   | [participacion-de-las-exportaciones-mineras-por-rubro-en-el-total-de-las-exportaciones](https://argendata.fund.ar/graficos/participacion-de-las-exportaciones-mineras-por-rubro-en-el-total-de-las-exportaciones/)                                     |
| Exportaciones mineras por grupo de minerales                                                            | [exportaciones-mineras-por-grupo-de-minerales](https://argendata.fund.ar/graficos/exportaciones-mineras-por-grupo-de-minerales/)                                                                                                                       |
| Importaciones mineras por grupo de minerales                                                            | [importaciones-mineras-por-grupo-de-minerales](https://argendata.fund.ar/graficos/importaciones-mineras-por-grupo-de-minerales/)                                                                                                                       |
| Balance comercial de productos minerales                                                                | [balance-comercial-de-productos-minerales](https://argendata.fund.ar/graficos/balance-comercial-de-productos-minerales/)                                                                                                                               |
| Índices de precios nominales internacionales de los principales metales                                 | [indices-de-precios-nominales-internacionales-de-los-principales-metales](https://argendata.fund.ar/graficos/indices-de-precios-nominales-internacionales-de-los-principales-metales/)                                                                 |
| Participación de la minería en el PIB provincial                                                        | [participacion-de-la-mineria-en-el-valor-agregado-bruto-provincial](https://argendata.fund.ar/graficos/participacion-de-la-mineria-en-el-valor-agregado-bruto-provincial/)                                                                             |
| Distribución provincial del PIB minero                                                                  | [distribucion-provincial-del-pib-minero](https://argendata.fund.ar/graficos/distribucion-provincial-del-pib-minero/)                                                                                                                                   |
| Exportaciones mineras en relación a las exportaciones provinciales totales                              | [exportaciones-mineras-en-relacion-a-las-exportaciones-provinciales-totales](https://argendata.fund.ar/graficos/exportaciones-mineras-en-relacion-a-las-exportaciones-provinciales-totales/)                                                           |
| Evolución del empleo minero                                                                             | [evolucion-del-empleo-minero](https://argendata.fund.ar/graficos/evolucion-del-empleo-minero/)                                                                                                                                                         |
| Categorías ocupacionales por rama                                                                       | [categoria-ocupacional-por-rama](https://argendata.fund.ar/graficos/categoria-ocupacional-por-rama/)                                                                                                                                                   |
| Tasa de feminización                                                                                    | [tasa-de-feminizacion-2](https://argendata.fund.ar/graficos/tasa-de-feminizacion-2/)                                                                                                                                                                   |
| Tasa de feminización por sector                                                                         | [tasa-de-feminizacion-por-sector](https://argendata.fund.ar/graficos/tasa-de-feminizacion-por-sector/)                                                                                                                                                 |
| Ventas de las grandes empresas mineras metalíferas                                                      | [descomposicion-de-las-ventas-de-las-grandes-empresas-mineras-metaliferas](https://argendata.fund.ar/graficos/descomposicion-de-las-ventas-de-las-grandes-empresas-mineras-metaliferas/)                                                               |
| Compras del sector minería agrupadas por rama vendedora                                                 | [compras-del-sector-mineria-agrupadas-por-rama-vendedora](https://argendata.fund.ar/graficos/compras-del-sector-mineria-agrupadas-por-rama-vendedora/)                                                                                                 |
| Importaciones mineras de bienes directas según rama industrial                                          | [importaciones-mineras-de-bienes-directas-segun-rama-industrial](https://argendata.fund.ar/graficos/importaciones-mineras-de-bienes-directas-segun-rama-industrial/)                                                                                   |
| Proyección del crecimiento de demanda de minerales para la transición energética                        | [proyeccion-del-crecimiento-de-demanda-de-minerales-para-la-transicion-energetica](https://argendata.fund.ar/graficos/proyeccion-del-crecimiento-de-demanda-de-minerales-para-la-transicion-energetica/)                                               |
| Minerales en la generación eléctrica por tipo de generación                                             | [minerales-en-la-generacion-electrica-por-tipo-de-generacion](https://argendata.fund.ar/graficos/minerales-en-la-generacion-electrica-por-tipo-de-generacion/)                                                                                         |
| Minerales utilizados por tipo de vehículo (combustión versus eléctrico)                                 | [minerales-utilizados-por-tipo-de-vehiculo-combustion-versus-electrico](https://argendata.fund.ar/graficos/minerales-utilizados-por-tipo-de-vehiculo-combustion-versus-electrico/)                                                                     |
| Posición argentina en la producción de minerales seleccionados                                          | [posicion-argentina-en-la-produccion-de-minerales-seleccionados-2](https://argendata.fund.ar/graficos/posicion-argentina-en-la-produccion-de-minerales-seleccionados-2/)                                                                               |

## [Pobreza](./POBREZ/)
[(volver al índice)](#índice)

| titulo                                                                   | link                                                                                                                                                                                     |
|:-------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Porcentaje de Hogares con NBI                                            | [porcentaje-de-hogares-con-nbi](https://argendata.fund.ar/graficos/porcentaje-de-hogares-con-nbi/)                                                                                       |
| Porcentaje de hogares con NBI según la provincia                         | [porcentaje-de-hogares-con-nbi-segun-la-provincia](https://argendata.fund.ar/graficos/porcentaje-de-hogares-con-nbi-segun-la-provincia/)                                                 |
| Porcentaje de personas pobres multidimensionales                         | [porcentaje-de-personas-pobres-multidimensionales](https://argendata.fund.ar/graficos/porcentaje-de-personas-pobres-multidimensionales/)                                                 |
| Porcentaje de personas pobres multidimensionales por región              | [porcentaje-de-personas-pobres-multidimensionales-por-region](https://argendata.fund.ar/graficos/porcentaje-de-personas-pobres-multidimensionales-por-region/)                           |
| Pobreza en Argentina                                                     | [pobreza-en-argentina](https://argendata.fund.ar/graficos/pobreza-en-argentina/)                                                                                                         |
| Tasas de pobreza monetaria en distintos países                           | [tasas-de-pobreza-monetaria-en-distintos-paises](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-en-distintos-paises/)                                                     |
| Tasas de pobreza monetaria en América Latina                             | [tasas-de-pobreza-monetaria-en-america-latina](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-en-america-latina/)                                                         |
| Tasas de pobreza monetaria para América Latina y Argentina               | [tasas-de-pobreza-monetaria-para-america-latina-y-argentina](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-para-america-latina-y-argentina/)                             |
| Tasas de pobreza monetaria por región                                    | [tasas-de-pobreza-monetaria-por-region](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-por-region/)                                                                       |
| Tasas de indigencia por región                                           | [tasas-de-indigencia-por-region](https://argendata.fund.ar/graficos/tasas-de-indigencia-por-region/)                                                                                     |
| Tasas de pobreza monetaria por género a nivel individual                 | [tasas-de-pobreza-monetaria-por-genero-a-nivel-individual](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-por-genero-a-nivel-individual/)                                 |
| Tasas de indigencia y pobreza por género del jefe de hogar               | [tasas-de-indigencia-y-pobreza-por-genero-del-jefe-de-hogar](https://argendata.fund.ar/graficos/tasas-de-indigencia-y-pobreza-por-genero-del-jefe-de-hogar/)                             |
| Tasas de pobreza monetaria según condición laboral                       | [tasas-de-pobreza-monetaria-segun-condicion-laboral](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-condicion-laboral/)                                             |
| Tasas de pobreza monetaria según relación laboral                        | [tasas-de-pobreza-monetaria-segun-relacion-laboral](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-relacion-laboral/)                                               |
| Tasas de pobreza monetaria según máximo nivel educativo alcanzado        | [tasas-de-pobreza-monetaria-segun-maximo-nivel-educativo-alcanzado-2](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-maximo-nivel-educativo-alcanzado-2/)           |
| Tasas de pobreza monetaria según máximo nivel educativo alcanzado        | [tasas-de-pobreza-monetaria-segun-maximo-nivel-educativo-alcanzado](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-maximo-nivel-educativo-alcanzado/)               |
| Tasas de pobreza monetaria según grupos etarios                          | [tasas-de-pobreza-monetaria-segun-grupos-etarios](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-grupos-etarios/)                                                   |
| Tasas de pobreza monetaria según características del hogar               | [tasas-de-pobreza-monetaria-segun-caracteristicas-del-hogar](https://argendata.fund.ar/graficos/tasas-de-pobreza-monetaria-segun-caracteristicas-del-hogar/)                             |
| Impacto de las transferencias estatales en tasas de pobreza e indigencia | [impacto-de-las-transferencias-estatales-en-tasas-de-pobreza-e-indigencia](https://argendata.fund.ar/graficos/impacto-de-las-transferencias-estatales-en-tasas-de-pobreza-e-indigencia/) |
| Impacto de las transferencias estatales en menores de 18 años            | [impacto-de-las-transferencias-estatales-en-menores-de-18-anos](https://argendata.fund.ar/graficos/impacto-de-las-transferencias-estatales-en-menores-de-18-anos/)                       |
| Pobreza en Argentina                                                     | [pobreza-en-argentina-2](https://argendata.fund.ar/graficos/pobreza-en-argentina-2/)                                                                                                     |

## [Inflación](./PRECIO/)
[(volver al índice)](#índice)

| titulo                                                             | link                                                                                                                                                                 |
|:-------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Índice de Precios al Consumidor en Argentina                       | [el-indice-de-precios-al-consumidor-ipc-en-argentina](https://argendata.fund.ar/graficos/el-indice-de-precios-al-consumidor-ipc-en-argentina/)                       |
| Índice de Precios al Consumidor en Argentina por región            | [el-indice-de-precios-al-consumidor-ipc-en-argentina-por-region](https://argendata.fund.ar/graficos/el-indice-de-precios-al-consumidor-ipc-en-argentina-por-region/) |
| Inflación anual promedio en el mundo entre 2007 y 2022             | [inflacion-anual-promedio-en-el-mundo-entre-2007-y-2022](https://argendata.fund.ar/graficos/inflacion-anual-promedio-en-el-mundo-entre-2007-y-2022/)                 |
| Inflación en el mundo                                              | [inflacion-en-el-mundo](https://argendata.fund.ar/graficos/inflacion-en-el-mundo/)                                                                                   |
| Inflación en América Latina y países de altos ingresos             | [la-inflacion-en-america-latina-y-los-paises-desarrollados](https://argendata.fund.ar/graficos/la-inflacion-en-america-latina-y-los-paises-desarrollados/)           |
| Inflación en Argentina y en América Latina                         | [la-inflacion-en-argentina-y-en-america-latina](https://argendata.fund.ar/graficos/la-inflacion-en-argentina-y-en-america-latina/)                                   |
| Gasto de consumo de los hogares                                    | [gasto-de-consumo-de-los-hogares](https://argendata.fund.ar/graficos/gasto-de-consumo-de-los-hogares/)                                                               |
| Precios relativos de bienes y servicios regulados                  | [precios-relativos-de-servicios-regulados](https://argendata.fund.ar/graficos/precios-relativos-de-servicios-regulados/)                                             |
| Precios relativos por capítulo del Índice de Precios al Consumidor | [precios-relativos-por-capitulo-del-ipc](https://argendata.fund.ar/graficos/precios-relativos-por-capitulo-del-ipc/)                                                 |
| Inflación en la Argentina                                          | [inflacion-en-la-argentina](https://argendata.fund.ar/graficos/inflacion-en-la-argentina/)                                                                           |
| Inflación en la Argentina (recortado)                              | [inflacion-en-la-argentina-log](https://argendata.fund.ar/graficos/inflacion-en-la-argentina-log/)                                                                   |

## [Salarios e ingresos](./SALING/)
[(volver al índice)](#índice)

| titulo                                                                                         | link                                                                                                                                                                                             |
|:-----------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ingreso per cápita familiar                                                                    | [ingreso-per-capita-familiar](https://argendata.fund.ar/graficos/ingreso-per-capita-familiar/)                                                                                                   |
| Ingreso per cápita familiar mensual en América Latina                                          | [ingreso-per-capita-familiar-mensual-en-america-latina](https://argendata.fund.ar/graficos/ingreso-per-capita-familiar-mensual-en-america-latina/)                                               |
| Ingreso per cápita familiar en Argentina y América Latina                                      | [ingreso-per-capita-familiar-en-argentina-y-america-latina](https://argendata.fund.ar/graficos/ingreso-per-capita-familiar-en-argentina-y-america-latina/)                                       |
| Ingreso per cápita familiar por región                                                         | [ingreso-per-capita-familiar-por-provincia](https://argendata.fund.ar/graficos/ingreso-per-capita-familiar-por-provincia/)                                                                       |
| Ingreso per cápita en las distintas regiones argentinas                                        | [ingreso-per-capita-en-las-distintas-regiones-argentinas](https://argendata.fund.ar/graficos/ingreso-per-capita-en-las-distintas-regiones-argentinas/)                                           |
| Participación del ingreso laboral en el ingreso total familiar                                 | [participacion-del-ingreso-laboral-en-el-ingreso-total-familiar](https://argendata.fund.ar/graficos/participacion-del-ingreso-laboral-en-el-ingreso-total-familiar/)                             |
| Fuentes del ingreso familiar total para cada decil                                             | [distintas-fuentes-en-el-ingreso-familiar-total](https://argendata.fund.ar/graficos/distintas-fuentes-en-el-ingreso-familiar-total/)                                                             |
| Fuentes del ingreso familiar total según edad del jefe de hogar                                | [distintas-fuentes-en-el-ingreso-familiar-total-2](https://argendata.fund.ar/graficos/distintas-fuentes-en-el-ingreso-familiar-total-2/)                                                         |
| Participación del ingreso laboral en el ingreso total familiar según género del jefe del hogar | [ingreso-laboral-en-el-ingreso-total-familiar-segun-genero-del-jefe-del-hogar](https://argendata.fund.ar/graficos/ingreso-laboral-en-el-ingreso-total-familiar-segun-genero-del-jefe-del-hogar/) |
| Distintas fuentes de ingresos no laborales                                                     | [distintas-fuentes-de-ingresos-no-laborales](https://argendata.fund.ar/graficos/distintas-fuentes-de-ingresos-no-laborales/)                                                                     |
| Ingreso laboral por hora e ingreso laboral mensual                                             | [ingreso-laboral-horario-e-ingreso-laboral-mensual](https://argendata.fund.ar/graficos/ingreso-laboral-horario-e-ingreso-laboral-mensual/)                                                       |
| Ingreso laboral por hora en países de América Latina                                           | [ingreso-laboral-horario-en-paises-de-america-latina](https://argendata.fund.ar/graficos/ingreso-laboral-horario-en-paises-de-america-latina/)                                                   |
| Ingreso laboral por hora en Argentina y América Latina                                         | [ingreso-laboral-horario-en-argentina-y-america-latina](https://argendata.fund.ar/graficos/ingreso-laboral-horario-en-argentina-y-america-latina/)                                               |
| Ingresos laborales por tipo de empleo                                                          | [ingresos-laborales-por-tipo-de-empleo](https://argendata.fund.ar/graficos/ingresos-laborales-por-tipo-de-empleo/)                                                                               |
| Ingresos laborales mensuales por edad y género                                                 | [ingresos-laborales-mensuales-por-edad-y-genero](https://argendata.fund.ar/graficos/ingresos-laborales-mensuales-por-edad-y-genero/)                                                             |
| Ingresos laborales por hora en la ocupación principal por edad y género                        | [ingresos-laborales-por-hora-en-la-ocupacion-principal-por-edad-y-genero](https://argendata.fund.ar/graficos/ingresos-laborales-por-hora-en-la-ocupacion-principal-por-edad-y-genero/)           |
| Evolución de los ingresos laborales reales por grupos etarios y género                         | [evolucion-de-los-ingresos-laborales-reales-por-grupos-etarios-y-genero](https://argendata.fund.ar/graficos/evolucion-de-los-ingresos-laborales-reales-por-grupos-etarios-y-genero/)             |
| Salario real en Argentina                                                                      | [salario-real-en-argentina](https://argendata.fund.ar/graficos/salario-real-en-argentina/)                                                                                                       |
| Salario real en países seleccionados                                                           | [salario-real-en-paises-seleccionados](https://argendata.fund.ar/graficos/salario-real-en-paises-seleccionados/)                                                                                 |
| Brecha en el salario entre asalariados registrados y no registrados                            | [brecha-en-el-salario-entre-asalariados-registrados-y-no-registrados](https://argendata.fund.ar/graficos/brecha-en-el-salario-entre-asalariados-registrados-y-no-registrados/)                   |

## [Servicios basados en el conocimiento](./SEBACO/)
[(volver al índice)](#índice)

| titulo                                                                                  | link                                                                                                                                                                                                     |
|:----------------------------------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Relevancia de las ventas de SBC sobre el total nacional                                 | [relevancia-de-las-ventas-de-sbc-sobre-el-total-nacional](https://argendata.fund.ar/graficos/relevancia-de-las-ventas-de-sbc-sobre-el-total-nacional/)                                                   |
| Ventas del sector de Software y Servicios Informáticos (SSI) en Argentina               | [ventas-del-sector-de-ssi-en-argentina](https://argendata.fund.ar/graficos/ventas-del-sector-de-ssi-en-argentina/)                                                                                       |
| Valor Agregado Bruto (VAB) del sector de software y servicios informáticos en Argentina | [valor-agregado-bruto-vab-del-sector-de-software-en-argentina](https://argendata.fund.ar/graficos/valor-agregado-bruto-vab-del-sector-de-software-en-argentina/)                                         |
| Exportaciones de SBC                                                                    | [exportaciones-de-sbc](https://argendata.fund.ar/graficos/exportaciones-de-sbc/)                                                                                                                         |
| Cantidad de puestos de trabajo registrados en el sector privado de SBC                  | [cantidad-de-puestos-de-trabajo-registrados-en-el-sector-privado-de-sbc](https://argendata.fund.ar/graficos/cantidad-de-puestos-de-trabajo-registrados-en-el-sector-privado-de-sbc/)                     |
| Principales provincias empleadoras de trabajadores SBC                                  | [principales-provincias-empleadoras-de-trabajadores-sbc](https://argendata.fund.ar/graficos/principales-provincias-empleadoras-de-trabajadores-sbc/)                                                     |
| Empleo formal de SBC en las distintas provincias                                        | [empleo-formal-de-sbc-en-las-distintas-provincias](https://argendata.fund.ar/graficos/empleo-formal-de-sbc-en-las-distintas-provincias/)                                                                 |
| Gasto en I+D de las empresas del sector SBC en Argentina                                | [gasto-en-id-de-las-empresas-del-sector-sbc](https://argendata.fund.ar/graficos/gasto-en-id-de-las-empresas-del-sector-sbc/)                                                                             |
| Composición del empleo asalariado formal por rama de SBC                                | [composicion-del-empleo-asalariado-formal-por-rama-de-sbc](https://argendata.fund.ar/graficos/composicion-del-empleo-asalariado-formal-por-rama-de-sbc/)                                                 |
| Empleados según rubro en relación con el empleo registrado privado total                | [empleados-segun-rubro-y-relacion-con-el-empleo-registrado-privado-total](https://argendata.fund.ar/graficos/empleados-segun-rubro-y-relacion-con-el-empleo-registrado-privado-total/)                   |
| Tasa de ocupados según condición laboral                                                | [tasa-de-ocupados-segun-condicion-laboral](https://argendata.fund.ar/graficos/tasa-de-ocupados-segun-condicion-laboral/)                                                                                 |
| Salario promedio de SBC, SSI y resto de la economía                                     | [salario-promedio-de-sbc-ssi-y-resto-de-la-economia](https://argendata.fund.ar/graficos/salario-promedio-de-sbc-ssi-y-resto-de-la-economia/)                                                             |
| Proporción de ocupados por nivel educativo                                              | [proporcion-de-ocupados-por-nivel-educativo](https://argendata.fund.ar/graficos/proporcion-de-ocupados-por-nivel-educativo/)                                                                             |
| Tasa de participación femenina en SBC y en el total del sector privado registrado       | [tasa-de-participacion-femenina-en-sbc-y-sector-privado-total](https://argendata.fund.ar/graficos/tasa-de-participacion-femenina-en-sbc-y-sector-privado-total/)                                         |
| Tasa de participación femenina en SSI y en el total del sector privado registrado       | [tasa-de-participacion-femenina-en-ssi-y-total-sector-privado-registrado](https://argendata.fund.ar/graficos/tasa-de-participacion-femenina-en-ssi-y-total-sector-privado-registrado/)                   |
| Brecha salarial de género en SSI y en el total de la economía                           | [brecha-salarial-de-genero-en-la-industria-de-software-y-total-economia](https://argendata.fund.ar/graficos/brecha-salarial-de-genero-en-la-industria-de-software-y-total-economia/)                     |
| Tasa de trabajo remoto en SBC                                                           | [tasa-de-trabajo-remoto-en-sbc](https://argendata.fund.ar/graficos/tasa-de-trabajo-remoto-en-sbc/)                                                                                                       |
| Exportaciones, importaciones y saldo comercial de los SBC                               | [exportaciones-importaciones-y-saldo-comercial-de-los-sbc](https://argendata.fund.ar/graficos/exportaciones-importaciones-y-saldo-comercial-de-los-sbc/)                                                 |
| Saldo comercial de SBC por rubro                                                        | [saldo-comercial-de-sbc-por-rubro](https://argendata.fund.ar/graficos/saldo-comercial-de-sbc-por-rubro/)                                                                                                 |
| Exportaciones de SBC por tipo de servicio                                               | [exportaciones-de-sbc-por-tipo-de-servicio](https://argendata.fund.ar/graficos/exportaciones-de-sbc-por-tipo-de-servicio/)                                                                               |
| Exportaciones de software en relación con las exportaciones totales de Argentina        | [exportaciones-de-software-en-relacion-con-las-exportaciones-totales-de-argentina](https://argendata.fund.ar/graficos/exportaciones-de-software-en-relacion-con-las-exportaciones-totales-de-argentina/) |
| Relevancia de cada país en las exportaciones mundiales de SBC                           | [relevancia-de-cada-pais-en-las-exportaciones-mundiales-de-sbc](https://argendata.fund.ar/graficos/relevancia-de-cada-pais-en-las-exportaciones-mundiales-de-sbc/)                                       |
| Participación de las exportaciones SSI en el comercio internacional según país          | [participacion-de-las-exportaciones-ssi-segun-pais-en-el-comercio-internacional](https://argendata.fund.ar/graficos/participacion-de-las-exportaciones-ssi-segun-pais-en-el-comercio-internacional/)     |
| Exportaciones argentinas de SBC por socio comercial                                     | [exportaciones-argentinas-de-sbc-por-socio-comercial](https://argendata.fund.ar/graficos/exportaciones-argentinas-de-sbc-por-socio-comercial/)                                                           |
| Importaciones argentinas de SBC según país de origen                                    | [importaciones-argentinas-de-sbc-segun-pais-de-origen](https://argendata.fund.ar/graficos/importaciones-argentinas-de-sbc-segun-pais-de-origen/)                                                         |

## [Transición energética](./TRANEN/)
[(volver al índice)](#índice)

| titulo                                                    | link                                                                                                                                                       |
|:----------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| Trilema energético                                        | [trilema-energetico](https://argendata.fund.ar/graficos/trilema-energetico/)                                                                               |
| Clasificación de las fuentes de energía                   | [clasificacion-de-las-fuentes-de-energia](https://argendata.fund.ar/graficos/clasificacion-de-las-fuentes-de-energia/)                                     |
| Fuentes de energía según nivel de contaminación           | [fuentes-de-energia-segun-nivel-de-contaminacion](https://argendata.fund.ar/graficos/fuentes-de-energia-segun-nivel-de-contaminacion/)                     |
| Identidad de Kaya                                         | [identidad-de-kaya](https://argendata.fund.ar/graficos/identidad-de-kaya/)                                                                                 |
| Consumo energético global                                 | [consumo-energetico-global](https://argendata.fund.ar/graficos/consumo-energetico-global/)                                                                 |
| Consumo energético en Argentina                           | [consumo-energetico-en-argentina](https://argendata.fund.ar/graficos/consumo-energetico-en-argentina/)                                                     |
| Matriz energética en Argentina                            | [matriz-energetica-en-argentina](https://argendata.fund.ar/graficos/matriz-energetica-en-argentina/)                                                       |
| Participación de energías limpias en la matriz energética | [participacion-de-energias-limpias-en-la-matriz-energetica](https://argendata.fund.ar/graficos/participacion-de-energias-limpias-en-la-matriz-energetica/) |
| Consumo energético por fuente                             | [consumo-energetico-por-fuente](https://argendata.fund.ar/graficos/consumo-energetico-por-fuente/)                                                         |
| Generación de energía hidroeléctrica                      | [generacion-de-energia-hidroelectrica](https://argendata.fund.ar/graficos/generacion-de-energia-hidroelectrica/)                                           |
| Generación de energía nucleoeléctrica                     | [generacion-de-energia-nucleoelectrica](https://argendata.fund.ar/graficos/generacion-de-energia-nucleoelectrica/)                                         |
| Capacidad instalada de energía solar                      | [capacidad-instalada-de-energia-solar](https://argendata.fund.ar/graficos/capacidad-instalada-de-energia-solar/)                                           |
| Capacidad instalada de energía eólica                     | [capacidad-instalada-de-energia-eolica](https://argendata.fund.ar/graficos/capacidad-instalada-de-energia-eolica/)                                         |
| Producción de biocombustibles                             | [generacion-de-biocombustibles](https://argendata.fund.ar/graficos/generacion-de-biocombustibles/)                                                         |
| Generación eléctrica global                               | [generacion-electrica-global](https://argendata.fund.ar/graficos/generacion-electrica-global/)                                                             |
| Generación eléctrica en Argentina                         | [generacion-electrica-en-argentina](https://argendata.fund.ar/graficos/generacion-electrica-en-argentina/)                                                 |
| Fuentes de generación eléctrica                           | [fuentes-de-generacion-electrica](https://argendata.fund.ar/graficos/fuentes-de-generacion-electrica/)                                                     |
| Generación de energía renovable local                     | [generacion-de-energia-renovable-local](https://argendata.fund.ar/graficos/generacion-de-energia-renovable-local/)                                         |
| Determinantes de las emisiones globales de carbono        | [determinantes-de-las-emisiones-globales-de-carbono](https://argendata.fund.ar/graficos/determinantes-de-las-emisiones-globales-de-carbono/)               |
| Determinantes de las emisiones de carbono en Argentina    | [determinantes-de-las-emisiones-de-carbono-en-argentina](https://argendata.fund.ar/graficos/determinantes-de-las-emisiones-de-carbono-en-argentina/)       |
| Intensidad energética                                     | [intensidad-energetica](https://argendata.fund.ar/graficos/intensidad-energetica/)                                                                         |
| Intensidad de carbono de la matriz eléctrica en Argentina | [intensidad-de-carbono-de-la-matriz-electrica-en-argentina](https://argendata.fund.ar/graficos/intensidad-de-carbono-de-la-matriz-electrica-en-argentina/) |
| Intensidad de carbono de la matriz eléctrica global       | [intensidad-de-carbono-de-la-matriz-electrica-global](https://argendata.fund.ar/graficos/intensidad-de-carbono-de-la-matriz-electrica-global/)             |



## Esquema del sistema de archivos
```
├── TOPICO
├── ...
├── CAMCLI
│   ├── dataset.csv
│   ├── dataset.json
│   └── ...
└── COMEXT
    ├── cambio_destinos_exportacion.csv
    ├── cambio_destinos_exportacion.json
    ├── cambio_origenes_importacion.csv
    ├── cambio_origenes_importacion.json
    ├── composicion_exportaciones_bienes_diferenciado_Bernini.csv
    ├── composicion_exportaciones_bienes_diferenciado_Bernini.json
    ├── composicion_exportaciones_bienes_regiones_mundo.csv
    ├── composicion_exportaciones_bienes_regiones_mundo.json
    ├── composicion_exportaciones_bienes_sectores_Brambilla_Porto.csv
    ├── composicion_exportaciones_bienes_sectores_Brambilla_Porto.json
    ├── composicion_exportaciones_bienes_sitc_seccion.csv
    ├── composicion_exportaciones_bienes_sitc_seccion.json
    ├── composicion_exportaciones_servicios_EBOPS_2digitos_agrupado.csv
    ├── composicion_exportaciones_servicios_EBOPS_2digitos_agrupado.json
    └── ...
```

En el ejemplo, para el tópico de **[Comercio Exterior](https://argendata.fund.ar/topico/comercio-exterior/)**(`COMEXT`) se visualizan archvios `.csv` y `.json` asociados a cada uno de los items (`cambio_destinos_exportacion`, por ejemplo). El primero de ellos contiene los datos. El segundo también incluye los metadatos asociados (fuente de información, institución productora, fechas de procesamiento, etc.):


### `cambio_destinos_exportacion.csv` [^3]
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

[^2]: El flujo de trabajo definido para la reproductibilidad cuenta con una librería de `R` que reune un conjunto de funciones para facilitar el flujo de trabajo con fuentes y recursos en Argendata [https://github.com/argendata/argendataR](https://github.com/argendata/argendataR)

[^3]: El código que genera esta salida es parte del proceso de ETL y puede consultarse en el _script_ [`18_cambio_destinos_exportacion.R`](https://github.com/argendata/etl/blob/main/scripts/subtopicos/COMEXT/18_cambio_destinos_exportacion.R)

<div>
<a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/6ef27bf9-141f-4537-9d78-e16b80196959">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/aa8e7c72-4fad-403a-a8b9-739724b4c533">
    <img src="fund.ar"></img>
  </picture>
</a>
</div>
