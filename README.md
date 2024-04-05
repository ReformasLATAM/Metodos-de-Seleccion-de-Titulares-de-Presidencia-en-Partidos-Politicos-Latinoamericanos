# Métodos de Selección de Titulares de Presidencia en Partidos Políticos Latinoamericanos

Bienvenidos/as al repositorio GitHub de la base de datos "Métodos de Selección de Titulares de Presidencia en Partidos Políticos Latinoamericanos", mantenido por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)

## Resumen

La base de datos contiene información sobre los procesos de selección que los partidos políticos en América Latina realizan para nombrar a sus autoridades. La recolección de información se realizó mediante la consulta de los estatutos de una muestra de 54 partidos políticos en América Latina. Principalmente se revisaron las reglas estatutarias de los métodos de selección de las autoridades partidistas.

La regulación del proceso de selección interna de autoridades partidistas se refiere a las características normativas estatutarias que establecen el tipo o tipos de métodos y procedimientos que pueden adoptar los partidos políticos para seleccionar a sus autoridades. La base de datos contiene información sobre los artículos estatutarios donde se estipulan los métodos de selección de autoridades, sí los titulares de presidencia pertenecen al Comité Ejecutivo Nacional del partido, así como sobre cuáles son los métodos y órganos para realizar el proceso de selección.

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. La persona responsable de la recopilación de los datos es Carlos Guadarrama
 Cruz (FES Acatlán UNAM, México), mientras que las personas responsables de la codificación de los datos son Carlos Guadarrama Cruz (Facultad de Estudios Superiores Acatlán, México); Jazmín Jimena Álvarez Enríquez (Facultad de Estudios Superiores Acatlán, UNAM) y Karla Estrada López (Facultad de Estudios Superiores Acatlán, UNAM).

## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_SPP` en el cual se encuentra toda la información relevante respecto a la base de datos vinculada a los métodos de selección de titulares de presidencia en partidos políticos latinoamericanos. En específico, la base de datos se compone de las siguientes variables:

-   `país`: nombre del país en el cual se llevó a cabo la reforma al régimen electoral en América Latina.

-   `cowcode`: código del país de acuerdo con la codificación de “Correlates of War”
https://correlatesofwar.org/data-sets/cow-country-codes.

-   `siglas_pais`: siglas del país de acuerdo con el código de tres letras ISO (por ejemplo: ARG, MEX, SAL) disponible en: http://utils.mucattu.com/iso_3166-1.html 

-   `id_partido`: clave numérica para identificar a cada uno de los 54 partidos políticos en la base de datos. El número se compone del número del país y el número del partido de la muestra por país.

-   `siglas_partido`: siglas de los nombres de cada uno de los 54 partidos políticos en la base de datos, de acuerdo con fuentes documentales de los propios partidos políticos.

-   `año_estatuto`: año de publicación de los estatutos de los partidos políticos entre 1996 y 2021, en los cuales se consultaron las reglas internas sobre la selección de autoridades partidistas en los órganos de dirección nacionales. En caso de que la información no esté disponible se usa el número -9999.

-   `articulo_estatuto`: indica el número del artículo de los estatutos partidos políticos donde se establecen las normas para la selección de autoridades partidistas. En caso de que la información no esté disponible se usa el número -9999.

-   `miembro_cen`: registra si las autoridades partidistas forman parte o no del Comité Ejecutivo Nacional (CEN) del partido político. Sus valores son No [0]: Las autoridades partidistas no son miembros del CEN; Sí [1]: Las autoridades partidistas sí son miembros del CEN.

-   `método_de_seleccion`: indica cuál es el método de selección de las autoridades partidistas de acuerdo con los estatutos de los partidos políticos. Sus valores son Convención o Asamblea [1]: Los estatutos establecen que la selección de las autoridades del partido será a través de la realización de una Convención o Asamblea de la organización; Internas cerradas [2]: Los estatutos establecen que la selección de las autoridades del partido serán a través del voto directo de las personas afiliadas a la organización; Junta de notables [3]: Los estatutos establecen que un grupo selecto de personas de la organización serán encargadas de seleccionar a las autoridades del partido.

-   `órgano_selector`: indica cuáles son los órganos específicos de dirección establecidas en sus estatutos. Sus valores son Asamblea [1]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas a las Asambleas Nacionales o su equivalente; Elección Interna [2]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas de Elección Interna o su equivalente; Directorio [3]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas a los Directorios o su equivalente; Convención [4]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas a Convenciones o su equivalente; Comité [5]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas a los Comités Ejecutivos Nacionales o su equivalente; Consejo [6]: Los estatutos de los partidos políticos establecen como uno de los órganos de dirección de las autoridades partidistas a los Consejos Políticos Nacionales o su equivalente.

## Citado

``` r
Freidenberg, Flavia. Dir., 2023, “Métodos de selección de titulares de presidencia en partidos políticos latinoamericanos”, Observatorio de Reformas Políticas en América Latina (1978-2023). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos (SFD/OEA), V1. DOI: https://doi.org/10.5281/zenodo.7922194 
```