#ESTATUS_Y_CBA_2023_SARDINACOMUN



Este repositorio contiene los archivos utilizados para el cálculo de CBA inicial 2023 de sardina común de las Regiones de Valparaíso a Los Lagos.


## CARPETAS

-  **Datos_junio** contiene los archivos excell enviados por seguimiento, descarte, edad y crecimiento y evaluaciones directa. Contiene los desembarques 2021 y 2022, composiciones de tallas y edades de la flota 2021/2022, pesos medios e iniciales, biomasas cruceros de verano y otoño.

-  **codigos_admb** contiene los archivos ADMB (.dat, .tpl) utilizados para las asesorías de septiembre 2021, marzo 2022, julio 2022 y MAE922 (MAE0921, MAE322, MAE722,MAE922).

- **funciones** contiene las funciones utilizadas para generar los escenarios de análisis retrospectivos, perfiles de verosimilitud, CBAs, entre otros.


- **CBA_sep** contienen los escenarios de CBA 2023 calculadas bajo tres escenarios de reclutamientos en las asesorías de septiembre 2022.

- **Retrospectivo_sept** contiene los escenarios utilizados para el análisis retrospectivo descontando 5 años a la serie, realizado para la asesoría de septiembre 2022.

- **Verosimilitud_sept** contiene los escenarios utilizados para generar los perfiles de verosimilitud fijando un rango de valores de Ro. Realizado para las asesorías de  septiembre 2022.

- **rep_AsesoriasPrevias** contiene los reportes de asesorías previas para realizar la comparación con las salidas del modelo actual.

- **Figuras** y **Tablas** contienen las Figuras y Tablas generadas por el código Rmd llamado *FigyTab_PrimerInforme*.

- **SUBDECON_483-259** contiene PRIMER INFORME, base de datos y FAI listos para ser enviados a revisión


## ARCHIVOS

### Archivos para referencias

- **apa_1** archivo .csl permite generar las referencias en formato APA 7ma edición

- **Referencias_noviembre2021** archivo BibTeX que guarda las referencias que serán utilizada en tercer informe

### Archivos para portadas

- **PORTADA_INICIAL** archivo en formato LATEX genera la portada en formato PDF que se pega al inicio del documento 

- **PORTADA_FINAL** archivo en formato LATEX genera la portada en formato PDF que se pega al final del documento 

### Archivos Rmarkdown

- **FigyTab_PrimerInforme** archivo que corre el código  MAE922, corre los escenarios para análisis retrospectivo, verosimilitud y CBA. genera las Figuras y tablas utilizadas en archivo llamado *PRIMERINFORME_SardComun_sept2022*. 

- **PRIMERINFORME_SardComun_sept2022** genera el PRIMER INFORME DE ESTATUS 2021/2022 Y CBA 2023 correspondiente a la asesoría de septiembre 2022.




