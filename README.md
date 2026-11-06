# Tlaxcala: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Tlaxcala, Mexico, which global-law reads at `mexico/tlaxcala/acts/`.

The law of the State of Tlaxcala (Estado Libre y Soberano de Tlaxcala, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-tla/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

129 ordenamientos with 532 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE TLAXCALA | 87 | as first published, then each reform: 3 October 1918 to 2 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO LIBRE Y SOBERANO DE TLAXCALA | 35 | as first published, then each reform: 20 November 1976 to 19 June 2024 |
| `codigo-de-bioetica-para-el-personal-de-salud/` | CODIGO DE BIOETICA PARA EL PERSONAL DE SALUD DEL ESTADO DE TLAXCALA | 1 | as first published: 6 November 2014 |
| `codigo-de-procedimientos-civiles/` | CODIGO DE PROCEDIMIENTOS CIVILES PARA EL ESTADO LIBRE Y SOBERANO DE TLAXCALA | 17 | as first published, then each reform: 20 November 1980 to 5 September 2018 |
| `codigo-financiero/` | CODIGO FINANCIERO PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 44 | as first published, then each reform: 1 January 2003 to 29 November 2025 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE TLAXCALA | 40 | as first published, then each reform: 1 June 2013 to 6 June 2026 |
| `codigo-reglamentario-en-materia-de-responsabilidades-adminis/` | CODIGO REGLAMENTARIO EN MATERIA DE RESPONSABILIDADES ADMINISTRATIVAS DEL ORGANO INTERNO DE CONTROL MUNICIPAL DEL AYUNTAMIENTO DE HUAMANTLA, ESTADO DE TLAXCALA | 1 | as first published: 31 August 2023 |
| `ley-de-adopciones/` | LEY DE ADOPCIONES PARA EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 5 September 2018 to 26 August 2020 |
| `ley-de-adquisiciones-arrendamientos-y-servicios/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y SERVICIOS DEL ESTADO DE TLAXCALA | 1 | as first published: 7 January 2003 |
| `ley-de-aguas/` | LEY DE AGUAS PARA EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 23 December 2009 to 11 May 2021 |
| `ley-de-amnistia/` | LEY DE AMNISTIA PARA EL ESTADO DE TLAXCALA | 1 | as first published: 29 May 2021 |
| `ley-de-apicultura/` | LEY DE APICULTURA | 1 | as first published: 7 October 2000 |
| `ley-de-arancel-judicial/` | LEY DE ARANCEL JUDICIAL PARA EL ESTADO DE TLAXCALA | 1 | as first published: 24 February 1949 |
| `ley-de-archivos/` | LEY DE ARCHIVOS DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 11 May 2021 to 4 October 2023 |
| `ley-de-areas-naturales-protegidas/` | LEY DE AREAS NATURALES PROTEGIDAS DEL ESTADO DE TLAXCALA | 1 | as first published: 5 April 2024 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE TLAXCALA | 1 | as first published: 5 September 2018 |
| `ley-de-asistencia-social/` | LEY DE ASISTENCIA SOCIAL PARA EL ESTADO DE TLAXCALA | 6 | as first published, then each reform: 1 April 2004 to 10 December 2025 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE TLAXCALA | 1 | as first published: 14 September 2021 |
| `ley-de-asociaciones-y-federaciones-agricolas-ganaderas-e-ind/` | LEY DE ASOCIACIONES Y FEDERACIONES AGRICOLAS, GANADERAS E INDUSTRIALES EN EL ESTADO DE TLAXCALA | 1 | as first published: 7 January 1959 |
| `ley-de-bibliotecas/` | LEY DE BIBLIOTECAS DEL ESTADO DE TLAXCALA | 1 | as first published: 11 April 2003 |
| `ley-de-bienestar-animal/` | LEY DE BIENESTAR ANIMAL PARA EL ESTADO DE TLAXCALA | 1 | as first published: 31 December 2022 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE TLAXCALA | 1 | as first published: 22 April 2023 |
| `ley-de-catastro/` | LEY DE CATASTRO DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 13 September 2016 to 4 October 2023 |
| `ley-de-ciencia-y-tecnologia/` | LEY DE CIENCIA Y TECNOLOGIA PARA EL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 27 December 2003 to 4 October 2023 |
| `ley-de-comunicaciones-y-transportes-en-el-estado-de-tlaxcala/` | LEY DE COMUNICACIONES Y TRANSPORTES EN EL ESTADO DE TLAXCALA | 6 | as first published, then each reform: 15 June 1983 to 19 December 2023 |
| `ley-de-condecoraciones-estimulos-y-recompensas-de-las-person/` | LEY DE CONDECORACIONES, ESTIMULOS Y RECOMPENSAS DE LAS PERSONAS INTEGRANTES DE LAS INSTITUCIONES DE SEGURIDAD CIUDADANA DEL ESTADO DE TLAXCALA | 1 | as first published: 21 February 2025 |
| `ley-de-consulta-ciudadana/` | LEY DE CONSULTA CIUDADANA PARA EL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 27 July 2006 to 4 October 2023 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE PARA EL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 15 December 2005 to 22 March 2024 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE TLAXCALA | 1 | as first published: 18 August 2004 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 15 October 2015 to 14 February 2023 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 4 | as first published, then each reform: 24 October 2008 to 19 September 2024 |
| `ley-de-disciplina-de-seguridad-ciudadana/` | LEY DE DISCIPLINA DE SEGURIDAD CIUDADANA DEL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 1 | as first published: 21 February 2025 |
| `ley-de-donacion-y-trasplantes-de-organos-tejidos-y-celulas/` | LEY DE DONACION Y TRASPLANTES DE ORGANOS, TEJIDOS Y CELULAS PARA EL ESTADO DE TLAXCALA | 1 | as first published: 14 October 2009 |
| `ley-de-educacion/` | LEY DE EDUCACION PARA EL ESTADO DE TLAXCALA | 9 | as first published, then each reform: 27 May 2020 to 30 June 2026 |
| `ley-de-educacion-superior/` | LEY DE EDUCACION SUPERIOR DEL ESTADO DE TLAXCALA | 1 | as first published: 20 May 2023 |
| `ley-de-ejecucion-de-sanciones-penales-y-medidas-restrictivas/` | LEY DE EJECUCION DE SANCIONES PENALES Y MEDIDAS RESTRICTIVAS DE LIBERTAD DEL ESTADO DE TLAXCALA | 1 | as first published: 3 June 2011 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA-RECEPCION PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 1 | as first published: 19 May 2011 |
| `ley-de-estimulos-y-recompensas-en-favor-de-los-maestros-y-pe/` | LEY DE ESTIMULOS Y RECOMPENSAS EN FAVOR DE LOS MAESTROS Y PERSONAS PARTICULARES QUE SE DISTINGAN POR SU COLABORACION EN LAS TAREAS DE LA CAMPAÑA DE ALFABETIZACION | 1 | as first published: 25 March 1965 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 1 | as first published: 16 May 2013 |
| `ley-de-fiscalizacion-superior-y-rendicion-de-cuentas/` | LEY DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 6 | as first published, then each reform: 25 December 2019 to 6 June 2026 |
| `ley-de-fomento-a-la-actividad-artesanal/` | LEY DE FOMENTO A LA ACTIVIDAD ARTESANAL DEL ESTADO DE TLAXCALA | 1 | as first published: 9 December 2004 |
| `ley-de-fomento-economico/` | LEY DE FOMENTO ECONOMICO DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 5 December 2009 to 4 October 2023 |
| `ley-de-fomento-para-la-lectura-y-el-libro/` | LEY DE FOMENTO PARA LA LECTURA Y EL LIBRO DEL ESTADO DE TLAXCALA | 1 | oldest version available: 23 December 2011 |
| `ley-de-fomento-y-proteccion-al-maiz-como-patrimonio-originar/` | LEY DE FOMENTO Y PROTECCION AL MAIZ COMO PATRIMONIO ORIGINARIO, EN DIVERSIFICACION CONSTANTE Y ALIMENTARIO, PARA EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 19 January 2011 to 24 May 2024 |
| `ley-de-gobernanza-digital/` | LEY DE GOBERNANZA DIGITAL DEL ESTADO DE TLAXCALA | 1 | as first published: 4 October 2023 |
| `ley-de-identidad-digital/` | LEY DE IDENTIDAD DIGITAL DEL ESTADO DE TLAXCALA | 1 | as first published: 20 June 2023 |
| `ley-de-igualdad-sustantiva-entre-mujeres-y-hombres/` | LEY DE IGUALDAD SUSTANTIVA ENTRE MUJERES Y HOMBRES DEL ESTADO DE TLAXCALA | 1 | as first published: 12 February 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE TLAXCALA PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 November 2025 |
| `ley-de-ingresos-del-municipio-de-acuamanala-de-miguel-hidalg/` | LEY DE INGRESOS DEL MUNICIPIO DE ACUAMANALA DE MIGUEL HIDALGO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-amaxac-de-guerrero-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE AMAXAC DE GUERRERO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-apetatitlan-de-antonio-carv/` | LEY DE INGRESOS DEL MUNICIPIO DE APETATITLAN DE ANTONIO CARVAJAL, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-cuapiaxtla-para-el-ejercici/` | LEY DE INGRESOS DEL MUNICIPIO DE CUAPIAXTLA, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-cuaxomulco-para-el-ejercici/` | LEY DE INGRESOS DEL MUNICIPIO DE CUAXOMULCO PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-el-carmen-tequexquitla-para/` | LEY DE INGRESOS DEL MUNICIPIO DE EL CARMEN TEQUEXQUITLA, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-espanita-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE ESPAÑITA, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-hueyotlipan-para-el-ejercic/` | LEY DE INGRESOS DEL MUNICIPIO DE HUEYOTLIPAN, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-lazaro-cardenas-para-el-eje/` | LEY DE INGRESOS DEL MUNICIPIO DE LAZARO CARDENAS, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-mazatecochco-de-jose-maria/` | LEY DE INGRESOS DEL MUNICIPIO DE MAZATECOCHCO DE JOSE MARIA MORELOS, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-munoz-de-domingo-arenas-par/` | LEY DE INGRESOS DEL MUNICIPIO DE MUÑOZ DE DOMINGO ARENAS, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-nativitas-tlaxcala-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE NATIVITAS, TLAXCALA PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 27 November 2025 |
| `ley-de-ingresos-del-municipio-de-panotla-para-el-ejercicio-f/` | LEY DE INGRESOS DEL MUNICIPIO DE PANOTLA, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-damian-texoloc-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN DAMIAN TEXOLOC, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-francisco-tetlanohcan-p/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN FRANCISCO TETLANOHCAN, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-jeronimo-zacualpan-para/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JERONIMO ZACUALPAN, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-jose-teacalco-para-el-e/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JOSE TEACALCO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-juan-huactzinco-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JUAN HUACTZINCO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-san-lucas-tecopilco-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN LUCAS TECOPILCO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-santa-apolonia-teacalco-par/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA APOLONIA TEACALCO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-santa-cruz-quilehtla-para-e/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA CRUZ QUILEHTLA, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-santa-cruz-tlaxcala-para-el/` | LEY DE INGRESOS DEL MUNICIPIO DE SANTA CRUZ TLAXCALA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-tepetitla-de-lardizabal-par/` | LEY DE INGRESOS DEL MUNICIPIO DE TEPETITLA DE LARDIZABAL, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-tepeyanco-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE TEPEYANCO, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-terrenate-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE TERRENATE, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 8 November 2025 |
| `ley-de-ingresos-del-municipio-de-tocatlan-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE TOCATLAN, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-totolac-para-el-ejercicio-f/` | LEY DE INGRESOS DEL MUNICIPIO DE TOTOLAC PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-tzompantepec-para-el-ejerci/` | LEY DE INGRESOS DEL MUNICIPIO DE TZOMPANTEPEC, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-xaltocan-para-el-ejercicio/` | LEY DE INGRESOS DEL MUNICIPIO DE XALTOCAN, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 19 November 2025 |
| `ley-de-ingresos-del-municipio-de-yauhquemehcan-para-el-ejerc/` | LEY DE INGRESOS DEL MUNICIPIO DE YAUHQUEMEHCAN, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-ingresos-del-municipio-de-ziltlaltepec-de-trinidad-sa/` | LEY DE INGRESOS DEL MUNICIPIO DE ZILTLALTEPEC DE TRINIDAD SANCHEZ SANTOS, PARA EL EJERCICIO FISCAL 2026, TLAXCALA | 1 | as first published: 15 November 2025 |
| `ley-de-instituciones-y-procedimientos-electorales/` | LEY DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES PARA EL ESTADO DE TLAXCALA | 11 | as first published, then each reform: 4 September 2015 to 29 August 2026 |
| `ley-de-justicia-penal-alternativa/` | LEY DE JUSTICIA PENAL ALTERNATIVA DEL ESTADO DE TLAXCALA | 1 | as first published: 11 December 2012 |
| `ley-de-la-comision-estatal-de-derechos-humanos/` | LEY DE LA COMISION ESTATAL DE DERECHOS HUMANOS | 6 | as first published, then each reform: 13 January 1999 to 19 June 2019 |
| `ley-de-la-construccion/` | LEY DE LA CONSTRUCCION DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 7 December 2013 to 11 February 2021 |
| `ley-de-la-juventud/` | LEY DE LA JUVENTUD PARA EL ESTADO DE TLAXCALA | 4 | as first published, then each reform: 4 November 2006 to 5 September 2018 |
| `ley-de-las-entidades-paraestatales/` | LEY DE LAS ENTIDADES PARAESTATALES DEL ESTADO DE TLAXCALA | 4 | as first published, then each reform: 14 October 1995 to 13 April 2018 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE TLAXCALA | 1 | as first published: 10 December 2025 |
| `ley-de-los-derechos-de-ninas-ninos-y-adolescentes/` | LEY DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE TLAXCALA | 14 | as first published, then each reform: 19 June 2015 to 29 January 2026 |
| `ley-de-mecanismos-alternativos-de-solucion-de-controversias/` | LEY DE MECANISMOS ALTERNATIVOS DE SOLUCION DE CONTROVERSIAS DEL ESTADO DE TLAXCALA | 1 | as first published: 13 March 2025 |
| `ley-de-medios-de-impugnacion-en-materia-electoral/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL PARA EL ESTADO DE TLAXCALA | 8 | as first published, then each reform: 1 January 2004 to 24 December 2024 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 14 May 2021 to 4 October 2023 |
| `ley-de-movilidad-y-seguridad-vial/` | LEY DE MOVILIDAD Y SEGURIDAD VIAL DEL ESTADO DE TLAXCALA | 1 | as first published: 5 April 2024 |
| `ley-de-obras-publicas/` | LEY DE OBRAS PUBLICAS PARA EL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 12 October 2004 to 25 May 2023 |
| `ley-de-partidos-politicos/` | LEY DE PARTIDOS POLITICOS PARA EL ESTADO DE TLAXCALA | 6 | as first published, then each reform: 4 September 2015 to 28 August 2020 |
| `ley-de-pensiones-civiles/` | LEY DE PENSIONES CIVILES DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 25 October 2013 to 24 December 2022 |
| `ley-de-profesiones/` | LEY DE PROFESIONES DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 6 March 1986 to 4 October 2023 |
| `ley-de-promociones-y-ascensos-para-las-personas-integrantes/` | LEY DE PROMOCIONES Y ASCENSOS PARA LAS PERSONAS INTEGRANTES DE LAS INSTITUCIONES DE SEGURIDAD CIUDADANA DEL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 1 | as first published: 21 February 2025 |
| `ley-de-proteccion-al-medio-ambiente-y-el-desarrollo-sostenib/` | LEY DE PROTECCION AL MEDIO AMBIENTE Y EL DESARROLLO SOSTENIBLE DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 3 June 2022 to 13 December 2023 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE TLAXCALA | 1 | as first published: 6 July 2013 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE TLAXCALA | 1 | as first published: 26 March 2026 |
| `ley-de-proteccion-para-los-no-fumadores-en-el-estado-de-tlax/` | LEY DE PROTECCION PARA LOS NO FUMADORES EN EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 31 July 1997 to 24 April 2008 |
| `ley-de-proteccion-y-atencion-a-los-sujetos-migrantes-y-sus-f/` | LEY DE PROTECCION Y ATENCION A LOS SUJETOS MIGRANTES Y SUS FAMILIAS PARA EL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 12 January 2017 to 25 February 2020 |
| `ley-de-proteccion-y-conservacion-de-monumentos-y-edificios/` | LEY DE PROTECCION Y CONSERVACION DE MONUMENTOS Y EDIFICIOS DEL ESTADO DE TLAXCALA | 1 | oldest version available: 18 January 1956 |
| `ley-de-proteccion-fomento-y-desarrollo-a-la-cultura-indigena/` | LEY DE PROTECCION, FOMENTO Y DESARROLLO A LA CULTURA INDIGENA PARA EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 8 April 2006 to 21 December 2013 |
| `ley-de-residuos/` | LEY DE RESIDUOS DEL ESTADO DE TLAXCALA | 1 | as first published: 16 June 2023 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 20 December 2016 to 4 October 2023 |
| `ley-de-responsabilidades-de-los-servidores-publicos/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS PARA EL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 1 January 2004 to 13 April 2018 |
| `ley-de-responsabilidades-sanciones-y-estimulos-de-los-servid/` | LEY DE RESPONSABILIDADES, SANCIONES Y ESTIMULOS DE LOS SERVIDORES PUBLICOS DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 10 October 1995 to 1 January 2004 |
| `ley-de-salud/` | LEY DE SALUD DEL ESTADO DE TLAXCALA | 19 | as first published, then each reform: 29 November 2000 to 19 February 2026 |
| `ley-de-salud-mental-y-del-comportamiento-adictivo/` | LEY DE SALUD MENTAL Y DEL COMPORTAMIENTO ADICTIVO DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 17 November 2023 to 19 December 2025 |
| `ley-de-seguridad-publica-y-ciudadana/` | LEY DE SEGURIDAD PUBLICA Y CIUDADANA DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 10 February 2024 to 8 October 2025 |
| `ley-de-sociedades-de-convivencia-solidaria/` | LEY DE SOCIEDADES DE CONVIVENCIA SOLIDARIA PARA EL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 12 January 2017 to 4 October 2023 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE TLAXCALA | 1 | as first published: 13 March 2026 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 3 June 2022 to 1 October 2025 |
| `ley-de-uniformes-escolares-gratuitos-para-alumnas-y-alumnos/` | LEY DE UNIFORMES ESCOLARES GRATUITOS PARA ALUMNAS Y ALUMNOS DE EDUCACION BASICA DEL ESTADO DE TLAXCALA | 1 | as first published: 22 November 2017 |
| `ley-de-victimas/` | LEY DE VICTIMAS DEL ESTADO DE TLAXCALA | 1 | as first published: 5 April 2024 |
| `ley-de-vivienda/` | LEY DE VIVIENDA DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 12 November 2010 to 17 November 2023 |
| `ley-de-voluntad-anticipada/` | LEY DE VOLUNTAD ANTICIPADA DEL ESTADO DE TLAXCALA | 1 | as first published: 28 December 2016 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE TLAXCALA | 3 | as first published, then each reform: 17 March 2021 to 31 May 2024 |
| `ley-del-control-constitucional/` | LEY DEL CONTROL CONSTITUCIONAL DEL ESTADO DE TLAXCALA | 5 | as first published, then each reform: 1 December 2001 to 6 June 2026 |
| `ley-del-instituto-tlaxcalteca-para-la-educacion-de-jovenes-y/` | LEY DEL INSTITUTO TLAXCALTECA PARA LA EDUCACION DE JOVENES Y PERSONAS ADULTAS, TLAXCALA --ANTES LEY DEL INSTITUTO TLAXCALTECA PARA LA EDUCACION DE LOS ADULTOS-- | 3 | as first published, then each reform: 23 May 2001 to 14 November 2025 |
| `ley-del-notariado/` | LEY DEL NOTARIADO PARA EL ESTADO DE TLAXCALA | 6 | as first published, then each reform: 13 February 2016 to 19 December 2025 |
| `ley-del-patrimonio-publico/` | LEY DEL PATRIMONIO PUBLICO DEL ESTADO DE TLAXCALA | 1 | as first published: 12 May 2005 |
| `ley-del-patronato-antonio-diaz-varela-del-municipio-de-chiau/` | LEY DEL PATRONATO ANTONIO DIAZ VARELA DEL MUNICIPIO DE CHIAUTEMPAN, TLAXCALA | 2 | as first published, then each reform: 19 May 2018 to 26 March 2022 |
| `ley-del-procedimiento-administrativo/` | LEY DEL PROCEDIMIENTO ADMINISTRATIVO DEL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 4 | as first published, then each reform: 1 December 2001 to 4 October 2023 |
| `ley-del-servicio-profesional-de-carrera-policial/` | LEY DEL SERVICIO PROFESIONAL DE CARRERA POLICIAL DEL ESTADO DE TLAXCALA Y SUS MUNICIPIOS | 1 | as first published: 4 March 2025 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 13 April 2018 to 15 October 2019 |
| `ley-ganadera/` | LEY GANADERA DEL ESTADO DE TLAXCALA | 2 | as first published, then each reform: 6 July 1978 to 18 October 2017 |
| `ley-laboral-de-los-servidores-publicos/` | LEY LABORAL DE LOS SERVIDORES PUBLICOS DEL ESTADO DE TLAXCALA, Y SUS MUNICIPIOS | 11 | as first published, then each reform: 1 January 2008 to 6 June 2026 |
| `ley-municipal/` | LEY MUNICIPAL DEL ESTADO DE TLAXCALA | 29 | as first published, then each reform: 21 December 2001 to 16 May 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 1 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
