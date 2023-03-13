# Changelog - VATSIM Argentina SectorFile

## v9.5.1 - 12/03/2023
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Incorporación de sector FAJO en archivo .ese

---

## v9.5 - 05/03/2023
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Se agregan aproximaciones de SADF como STAR para poder seleccionarlas
- Se corrigen STAR "7D" para RWY 31, considerando aproximación NDB.
- Se crea nueva "STAR" de pista 29 desde ESLAN
- Se mofician STARs UGIMI6A/B de SAEZ a pista 11/35, agreando el inicio desde ESLAN 
- Se crea posición SAEF_FSS (Ezeiza Radio), con sus puntos de coordinación con FAJO_FSS y SAEF, login profile y ASR.
- Se activa CPDLC para sector oceánico
- Correcciones en login profiles de SAEF y Baires
- Correcciones de simbología para el TAG profesional en Topsky
- Se actualiza el AIRAC al 2302

---

## v9.4 - 20/01/2023
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Actualización AIRAC 2213
- Creación de antenas de radar para poder utilizar el modo Profesional
- Actualización de pista de SARP
- Actualización de posiciones de estacionamiento de SARI
- Eliminación de posición de SAZV
- Incorporación de sistema PDC via Hoppie en Topsky (para uso en SABE y SAEZ)

---

## v9.3 - 13/10/2022
*Actualizado por Javier Escandarani, Mariano Lopez y Agustin Miglino*

- Se actualizan todas las STARs para incluir todos los fixes hasta el FAF, lo que facilita dar directos. 
- Se corrigen errores en SID/STAR de SAVC
- Se corrigen erroes en SID/STAR de SARC
- Se agregan aerolíneas faltantes
- Se actualiza al AIRAC 2210 
- Se actualiza el Plugin Topsky a la última versión
- Se agrega alertas MSAW en Córdoba Control (SACO APP)
- Se eliminan STARs de SUMU
- Se eliminan segmentos de aerovías no existentes (LYE-GEMSU y MLG-STO).

---

## v9.2.3 - 14/08/2022
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Corrección de STARs de SCEL
- Creación de RWYS en SCEL, SUMU, SCTE y SCSE para facilitar la selección de las STARs para los handoff.
- Se corrigen errores en puntos de coordinación (COPX)
- Se agregan colores a algunos elementos de las listas para facilitar la lectura de la información relevante de cada una.
- Se agregan aerolíneas faltantes
- Actualizaciòn de AIRAC v2208

---

## v9.2.2 - 30/07/2022
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Se agrega COPX entre Baires y SAEF para posición ATOVO que faltaba.
- Se corrigen SID y STAR de SANT.
- Se corrigen SID y STAR de SAME.
- Correcciones menores en el TAG Topsky.
- Correcciones de los ATZ de San Fernando, Palomar, Moreno, Campo de Mayo.
- Se agregan los FIXes de las aproximaciones de San Fernando
- Corrección de error en lista de STARs RWY 17 de SAEZ
- Se agregan Aerolíneas: JAP (Jetsmart Perú), BVX (Osprey), ABS (Aerobrasil).

---

## v9.2.1 - 22/06/2022
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Arreglo de los perfiles del vATIS
- Incorporación de coordinación silenciosa en el nuevo TAG
- Incorporación de menú Waypoint en donde se da el directo desde el TAG
- Incorporación de pista asignada en TAG
- Mejoras varias al TAG

---

## v9.2 - 17/06/2022
*Actualizado por Javier Escandarani, Mariano Lopez y Giuliano Viola*

- Actualización del AIRAC a 2206
- Eliminación del VOR Moreno (ENO)
- Se agregan STARs RNAV de SAEZ (11/35) y se eliminan las convecionales (6A/6B).
- Se agregan STARs RNAV a RWY 17 en SAEZ
- Se agregan STARs RNAV de SABE (RWY13) y se eliminan STARs convencionales RWY 13 (7C/8C).
- Se corrige STAR PAPIX1R de SABE (31)
- Se agregan STARs RNAV de SADP (17) y se eliminan las convecionales (7C).
- Se dibuja la aproximación RNP RWY 23 en SADF
- Se corrige identificación de SUMU TWR (de CAT a CRT) por conflicto con SANC.
- Se agregan aeronaves: A338/A339/TBM9
- Se corrijen taxiways de SARC
- Se eliminan las posiciones SARC_GND, SARE_GND, SAWC_GND, SAZY_GND.
- Se actualiza Topsky a su última versión
- Se crea nuevo TAG basado en el Plugin Topsky
- Se elimina el Holding Plugin (al estar incorporado al TAG de Topsky).
- Se incorporan los perfiles para vATIS V4.0, con los 5 FIR creados (y los respectivos ATIS dentro de cada FIR). Se incluyen los cálculos automáticos de nivel de transición para cada aeropuerto.

---

## v9.1 - 21/04/2022
*Actualizado por Javier Escandarani y Mariano Lopez*

- Actualización de STARs RWY 13 SABE para que terminen en VANAR (no FDO)
- Creación de salidas estandarizadas SADF
- Creación de salidas estandarizadas SADP
- Se dibujan las aproximaciones RNP a las 4 pistas de SACO (como STAR, en DISPLAY)
- Se dibuja la aproximación RNP 17 en SAEZ
- Se agrega posición SULS TWR
- Se crean STARs RWY 06/24 de SUMU desde DARKA
- Modificación del orden de las SID y STAR de SAZS y SAZB para que las RNAV aparezcan primero en las listas
- Actualización archivo vATIS de SABE para inlcuir perfil de LVP
- Se actualizan los puntos de coordinación entre Ezeiza y Baires con niveles preestablecidos de descenso
- Se actualizan los puntos de coordinación entre Baires y Aeroparque y Ezeiza
- Se actualizan los puntos de coordinación entre Aeroparque y San Fernando
- Se actualizan puntos de coordinación entre SUEO y SAEF/SACF

---

## v9.0 - 13/03/2022
*Actualizado por Javier Escandarani y Mariano Lopez*
- Corrección SID/STAR SAWC
- Corrección SID SANE
- Corrección SID/STAR SANT, se cambia el orden de las STAR de RWY02 para que se sugiera primero las RNAV
- Corrección SID SANU
- Corrección SID/STAR SARC
- Corrección SID SARE
- Corrección SID/STAR SARI
- Corrección SID SAVC
- Corrección SID SAWE 
- Corrección STAR SAAR
- Corrección STAR SASA
- Eliminación SID PWL de SAWH
- Se dibujan SID de SAZR
- Se modifica el orden de las STAR de SAZS, para que se sugieran primero las RNAV
- Se agrega al archivo .sct las llegadas estandarizadas de la pista 29 de SAEZ, para poder visualizarlas
- Se agregan pistas de varios aeropuertos de los FIR Ezeiza, Córdoba y Comodoro que no figuraban, impidiendo activar los aeropuertos (y departure list)
- Cambio de frecuencia de Córdoba Centro
- Se corrige error del Login de SARI TWR
- Se agregan los callsign de Aerolineas Virtual (ARV), Imperial (IAL) y Nova (NVA)
- Se agrega posibilidad de asumir tránsitos desde etiqueta de superficie
- Actualización AIRAC v2202

---

## v8.9 - 27/12/2021
*Actualizado por Javier Escandarani y Mariano Lopez*
- Incorporación de SID/STAR SAWC en archivo .ese
- Incorporación de llegadas de Puerto Montt y La Serena para coordinación
- Adaptación de ASRs de FIRs según nuevo AIRAC
- Incorporación de ASRs por aeropuerto, dependencia y pista en uso
- Incorporación de SABE_DEL como dependencia
- Incorporación de ASR para SAWC_TWR
- Reincorporación de puntos locales de aeródromo

---

## v8.8 - 16/12/2021
*Actualizado por Javier Escandarani y Mariano Lopez*
- Actualización de SID/STAR SAWC
- Actualización AIRAC v2112
- Actualización de aerovías de acuerdo a nuevo airac
- Incorporación de plugin de holding
- Cambio de orden en SIDs para priorización según operaciones
- Incorporación de llegadas de SCEL para coordinación

---

## v8.7 - 14/08/2021
*Actualizado por Javier Escandarani y Mariano Lopez*
- Actualización de AIRAC v2108
- Actualización de dependencias en base a nuevo LoA con VATSIM UK
- Incorporación de puntos faltantes en aproximación RNP SACO
- Incorporación de pista única en perfiles vATIS
- Incorporación de EGYP ATIS en perfiles vATIS
- Incorporación de instrucciones automáticas para Sweatbox (especiales agradecimientos a Alejandro Sosa)
- Incorporación de transponders para EGYP

---

## v8.6 - 03/08/2021
*Actualizado por Javier Escandarani y Mariano Lopez*
- Actualización de AIRAC v2107
- Mejoras en perfiles vATIS

---

## v8.5 - 31/07/2021
*Actualizado por Javier Escandarani y Mariano Lopez*
- Incorporación de puntos de coordinación entre SAEF y SAZT
- Incorporación de puntos de coordinación entre SAEF y SACF N/S
- Arreglos varios en ASRs
- Arreglos en login profiles
- Arreglos en aliases
- Arreglos en SSRs para SAVF
- Arreglos en SID y STAR de SAWH
- Incorporación de STAR ficticias para el dibujo de las llegadas estandarizadas
- Incorporación de SID y STAR en SARC
- Incorporación de nuevas dependencias en EGYP según nuevo LOA
- Incorporación de pista de MGI
- Incorporación de archivos para configuración de vATIS

---

## v8.4 - 05/06/2021
*Actualizado por Javier Escandarani*
- Generación de ASRs para todas las dependencias
- Actualización de dependencias
- Incorporación de dependencias en el listado inicial
- Incorporación de identificadores de puntos en los ASRs
- Actualización de AIRAC v2105
- Mejora de sistema de etiquetas
- Incorporación del Sector 1 de BAIRES
- Arreglos varios

---

## v8.3 - 17/04/2021
*Actualizado por Javier Escandarani*
- Incorporación de plugin TopSky para generación de SSRs
- Reorganización de ASRs
- Actualización de AIRAC v2103

---

## v8.2 - 06/03/2021
*Actualizado por Javier Escandarani*
- Modificación de frecuencias de SAEF_CTR, SAVF_CTR, SABE_TWR y SAEZ_TWR
- Incorporación de SAWH_ATIS
- Incorporación de SAM_F_FSS
- Rediseño Aeroparque (Agradecimientos a Alejandro Sosa y Esteban Palacios)
- Arreglo del sector límite con Chile (Agradecimientos a Mariano Lopez)
- Actualización de AIRAC v2102
- Mejora del changelog
- Arreglo de SAWH SIDs

---

## v8.1 - 16/01/2021
*Actualizado por Javier Escandarani*
- Fixes varios
- Modificación de listas para adaptar a nueva fraseología
- Arreglo de todos los puntos límites entre FIRs

---

## v8.0 - 28/11/2020
*Actualizado por Mariano Lopez y Javier Escandarani*
- Adaptación de la pantalla radar a la de la vida real
- Actualización de SID, STAR y RWYs y de todo el país
- Actualización de AIRAC a v2012
- Actualización de aerolíneas
- Actualización de aliases
- Arreglo de puntos y niveles de transferencia entre dependencias
- Incorporación de sonidos Gander

---

## v7.2 a,b, y c - 29/08/2020)
*Actualizado por Esteban Palacios*
- Se agrega Ezeiza Gnd Con las regiones y posiciones de estacionamiento actuales
- Se corrigio problemas con sid y star de aerodromos salen completos por pista y transicion
- Se remodelo SADM, SADJ
- Se agrego ils 35 y 11 saez
- Modificaron los atz de sadf sadp sadj sadm
- Se agrego atz campo de mayo
- Se agrago asr saez gnd y saez
- Se modifico los asr de sabe y baires
- Se agrego arco radar 100nm y 150nm de eze en saef
- Se modifico asr saef
- Se agrego region al aeropuerto de cordoba 
- Se creo asr para saco gnd
- Se agrego geo a saca y sace
- Se agrego ils pista 19 saco
- Se creo asr para el ctr de cordoba
- Se creo geo para cordoba control con minimos de nivel de vuelo
- Se creo asr para cordoba control
- Se corrio geo de sanl, sanc, sasj, saoc
- Se mejoro la region de sant y sasa
- Se corrigieron posiciones de estacionaminto, en toda la fir de cordoba
- Se modifico el asr de la fir de mendoza
- Se agrego region al aeropuerto de mendoza 
- Se creo asr para same gnd
- Se creo geo para mendoza control con minimos de nivel de vuelo
- Se creo asr para mendoza control
- Se corrio geo de samm, sanu, samr, saor, saos.
- Se corrigieron posiciones de estacionaminto, en toda la fir de mendoza
- Se modifico el asr de la fir de mendoza 

---

## v7.1 - 14/08/2020
*Actualizado por Esteban Palacios*
- Se corrigió problemas con sid y star de aerodromos(salian todos juntos)
- Se corrigió deparure list para los gnd
- Se agregó el airac 2009
- Se rediseñó el gnd de palomar ajustando las posiciones de estacionamiento
- Se rediseñó el gnd de san fernando ajustando las posiciones de estacionamiento
- Se rediseñó de geo a region san fernando y palomar
- Se agregó los ils de 13 de sabe y 17 de sadp
- Se optimizó el asr de sabe, dejandolo simil INDRA real
- Se agregó asr baires
- Se agregó asr sadp_gnd , sabe_gnd y sanfer_gnd

---

## v7.0 - 27/07/2020
*Actualizado por Javier Escandarani, Esteban Palacios & Mariano Lopez*
- Creación del sector desde 0 solo se mantuvo la base de los ARTCC
- Se separó los sectoresen artcc, artcc high, artcc low
- Se agregó el  atz de sadf,sadp,sadm,sadj
- Se rediseño el gnd de aeroparque ajustando las posiciones de estacionamiento
- Se agrega el sector aeroparque.gnd
- Se actualizaron punto, aerovias, vor, ndb, aerodromos, pistas, sid y star directamente desde el airac
- Se reacomodó el sistema de iluminación de espacios aereos interiores y adyacemtes conectados
- Se actualiza el sistema de armado de sectores.

---

## v6.4 - 03/06/2020
*Actualizado por Javier Escandarani & Mariano Lopez*
- Agrega puntos de transferencia entre Baires y Aeroparque/Ezeiza
- Agrega FUCSA
- Cambios en alertas
- Cambios en lineas de vectores
- Ajuste de visibilidades para los profiles
- Elimina plugins
- Ajustes en TAG

---

## v6.3 - 02/06/2020
*Actualizado por Javier Escandarani*
- Arregla voices channels
- Reemplaza SARGO por UGIMI
- Reemplaza columna E por C en departure list
- Actualiza frecuencias y posiciones ATIS de acuerdo con nuevas posiciones
- Actualiza frecuencias y posiciones GND de acuerdo con nuevas posiciones
- Actualiza frecuencias y posiciones TWR de acuerdo con nuevas posiciones
- Actualiza frecuencias y posiciones APP de acuerdo con nuevas posiciones
- Actualiza frecuencias y posiciones CTR de acuerdo con nuevas posiciones
- Actualiza colores del radar acorde al de la vida real
- Actualiza salidas de SADP acordes a cambio de pista
- Actualiza salidas de SACO acordes a cambio de pista
- Elementos de listas, posiciones y colores
- Readme.md
- Airac 2006
- Separación de SACF en sectores Centro, Norte y Sur
- Separación de SAVF en sectores Centro, Norte y Sur
- Muestra aerovias que estaban ocultas
- Remueve SADS
- Configuraciones varias
- Agrega todos los transponders nacionales para SAEF
- Agrega SADP GND y SADP ATIS

---

## v6.2 - 25/02/2020
*Actualizado por Pablo Lopez*
- Sector SABE_APP

---

## v6.1 - 11/02/2020
*Actualizado por Pablo Lopez*
- Airac 2003

---

## v6.0 - 10/01/2020
*Actualizado por Pablo Lopez*
- Airac 2001

---

## v5.9 - 09/12/2019
*Actualizado por Carlos Montenegro*
- Airacs 1912 - Rutas ATS y RNAV AMDT3 ANAC

---

## v5.8 - 25/11/2019
*Actualizado por Carlos Montenegro*
- Airacs 1912 - FIX/SID/STAR AMDT3 ANAC

---

## v5.7 - 21/10/2019
*Actualizado por Carlos Montenegro*
- Airacs 1911 - Y correccion de FIXs

---

## v5.6 - 07/09/2019
*Actualizado por Carlos Montenegro*
- Se actualizó con AMD ANAC 02/2019
- Se Agregó pista ripio SAAG
- Correcciones en SAZY, SAWH

---

## v5.5 - 16/08/2019
*Actualizado por Carlos Montenegro*
- Se actualizó a la AIRAC 1909
- Actualizacion y agregados de aeródromos

---

## v5.4 - 28/03/2019
*Actualizado por Agustin Miglino*
- Se saltea versión 5.3 a 5.4 a los efectos de correlacionar con numeración AIRAC
- Sector Actualizado al AIRAC 1904
- Actualización de archivo Vatsim Argentina.sct2
- Actualización de archivo Vatsim Argentina.ese
- Actualización de archivo login_profiles.txt
- Actualización de archivo voice_channels.txt

---

## v5.2 - 11/03/2019
*Actualizado por Agustin Miglino*
- Sector Actualizado al AIRAC 1903
- Actualización de archivo list.txt
- Actualización de archivo login_profiles.txt

---

## v5.1 - 14/01/2019
*Actualizado por Carlos Montenegro*
- Actualización Airacs para Euroscope V.1912

---

## v5.7 - 20/10/2019
*Actualizado por Martin Ongaro*
- FIXES faltantes agregados

	AKSAS S029.49.03.000 W058.09.39.000

	DEXAL S039.23.57.000 W067.52.13.000

	GESNI S034.16.27.000 W063.54.07.000

	IREXA S034.49.53.000 W063.59.22.000

	RIOKA S030.35.46.000 W058.18.37.000

	VAKAP S039.46.49.000 W064.43.10.000

	VUNSO S041.51.55.000 W066.12.57.000

- FIX SOVLI, TMA Malargue error de tipeo corregido
- FIXES desactualizados removidos: ILKOM, ISUGU, SEBMU
- FIXES duplicados removidos: MUBES, ILTIP
- VATSIM Argentina.sct2 configurado con FIXES mas importantes, ARTCC boundary, high airways, etc.
- Minor fixes de tipeo

---

## v5.0 - 13/01/2019
*Actualizado por Javier Escandarani*
-	Actualización AIRAC 1901
-	Reidentación del .sct2
-	Modificación de aerovías acorde a actualización AIP 31/01/2019
-	Modificación de waypoints acorde a actualización AIP 31/01/2019
-	Modificación de SIDs y STARs acorde a actualización AIP 31/01/2019
- Actualización de declinaciones magnéticas
- Incorporación de fijos utilizados en nuevas IAC RNP
-	Incorporación de señalización de calles de rodaje
-	Configuraciones varias

---

## v4.1 - 29/04/2017
*Actualizado por Javier Escandarani*
- Lineas de vectorización de RWY se activan dependiendo de la pista activa seleccionada en la lista
- Corrección de puntos de visibilidad en SAEF_CTR y SACF_CTR
- Eliminación del error en la primera vez que se abre el sector file
- Auto-display de METAR's de aeropuertos activos
- Actualización AIRAC 1704
- Incorporación de vCSS (Intercom)
- Incorporación de de ALIASES para coordinación

---

## v4.0 - 05/03/2017
*Actualizado por Javier Escandarani*
- Cambio de nombre de archivos acorde al cambio de nombre de la división
- Actualización AIRAC 1702
- Corrección de errores tales como nombres de FIXES, coordenadas y aerovías
- Incorporación de un ASR por FIR
- Corrección de SID y STAR en el .sct2
- Actualización de SID y STAR en el .ese
- Incorporación y modificación de ALIASES
- Creación de nueva etiqueta
- Creación y corrección de aeródromos tanto comerciales como de aviación general entre ellos SAZR, SANC, SAWE, SANE, SANU, SAOC, SAOU, SARC, SARP, SASJ, SAVC, SAMR, SAVV, SAVY, SAAI
- Eliminación de FIXES deprecados
- Incorporación de identificativos visibles de pistas para aeródromos más pequeños
- Corrección de identificativos y rumbos magnéticos de pistas de aeródromos en la sección RUNWAYS
- Incorporación de códigos IATA de aeródromos no controlados en el radar

---

## v3.2 - 02/12/2016
*Actualizado por Javier Escandarani*
- Incorporación de ALIASES para la comunicación con tránsitos por texto
- Cambios en la interfaz gráfica

---

## v3.1 - 26/10/2016
*Actualizado por Javier Escandarani*
- Incorporación de SAEF N CTR y SAEF S CTR
- Actualización de cartas de acuerdo a NOTAM 04/2016

---

## v3.0 - 22/09/2016
*Actualizado por Javier Escandarani*
- Modificación de aerovías y fixes con respecto a actualización de AIP's del 13/10/2016
- Corrección de lista de pistas disponibles y activas por declinación magnética
- Correcciones menores
- Actualización del AIRAC (1612)

---

## v2.4 (17/04/2016)
*Actualizado por Javier Escandarani*
- Incorporación de las SID y STAR de todos los aeropuertos argentinos
- Corrección de errores de relación entre identificativo y dependencia
- Actualización del AIRAC (1604)

---

## v2.3 (02/04/2016)
*Actualizado por Javier Escandarani*
- Actualización de frecuencias correspondientes a la nueva tabla de posiciones ATC en el Voice Communication Setup
- Actualización de frecuencias correspondientes a la nueva tabla de posiciones ATC en el archivo .ese
- SID SURBO7 de SABE agregada

---

## v2.2 (30/03/2016)
*Actualizado por Javier Escandarani*
- Corrección de coordenadas en SARE y SAWG
- Implementación de nuevas cartas SID y STAR en Resistencia y Gallegos (agregando también los fijos faltantes)

---

## v2.1 (28/03/2016)
*Actualizado por Javier Escandarani*
- Creación 2D del aeródromo Morón  (SADM)
- Corrección de dependencias (Córdoba) según nueva tabla de posiciones ATC
- Incorporación de aeródromos a CTR's para reconocer tránsitos dentro de sus zonas

---

## v2.0.2 beta - 13/08/2013 2353z
*Actualizado por Pablo Maciel*
- Corregido los sectores de SABE_TWR a los de SABE_APP
- Corregido los sectores de SAEZ_TWR a los de SAEZ_APP

---

## v2.0.1 beta
- Corregidos algunos errores en la lineas costeras
- Guia rápida mejorada
- Se incluye una segunda opcion para escenarios de SAEZ llamada "SAEZ opcion 2"; dibujada sólo por líneas

---

## v2.0 beta
*Escrito por Emiliano Ferraco para el ARTCC Argentino*
*(Se utilizaron lineas del archivo original ARTCC Argentino 2010).*
- Implementación del formato .sct2;
- Información ordenada y clasificada, para hacer más fácil su búsqueda y selección;
- Redibujado de los límites costeros y límites internacionales;
- Redibujado de los límites de los cinco FIRs;
- Selección independiente de cada FIR en la sección ARTCC;
- Corrección de errores en los límites de algunos TMAs y CTRs;
- Corrección de errores en datos lat/long de FIXES y VORs;
- Eliminación de datos innecesarios o en desuso;
- Incorporación de aerovías faltantes;
- Eliminación de rutas inexistentes;
- Eliminación datos erróneos de rutas existentes;
- Incorporación de SID/STARS faltantes;
- ATIS Voice
- Incorporación de gráficos 2D para algunos aeropuertos
(SABE, SAEZ, SACO, SANT, SAZS, SAAR);
- Mejora en los gráficos de otros aeropuertos
(SAME, SARI, SASA, SAWH, SAZM, SADF, SAWE, SAWG, SAWH, SAWC, SAVC, SAVT, SAVV);
- Incorporación de dos escenarios para SABE a elección: X-ARG y Argentina-Real;
- Archivos definidos para el Settings file setup:
	- Aliases.txt: incorpora aliases en inglés;
	- Voice_channels.txt: listado completo de ATCs y sus frecuencias;
	- Demás archivos...
- Programación del archivo .ESE que incorpora:
	- Textos en el RADAR Display (taxiways y parkings para aeropuertos);
	- Definiciones de POSICIONES, frecuencias de contacto y Puntos de Visibilidad;
	- Definiciones de SECTORES, con sus límites verticales
	(por ahora COMPLETOS FIRs de CORDOBA, EZEIZA y COMODORO RIVADAVIA)
	- Definiciones de PUNTOS DE COORDINACIÓN entre sectores
	(por ahora FIRs de CORDOBA, EZEIZA y COMODORO RIVADAVIA);

		 Compatibilidad de aeropuertos:
		SANT - Escenario de Roberto Waters
		SABE - Escenario de Argentina Real
		SAEZ - Escenario de TROPICALSIM
		SAME - Escenario de Argentina Real
		SARI - Escenario de Alcal Simulación
		SASA - Escenario de Argentina Real
		SACO - Escenario de Ivano Marongiu

---

## v1.0
-	ARTCC Argentino 2010