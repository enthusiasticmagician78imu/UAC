---
Title: "Historia de las bases de datos"
Curse: "MODELADO DDBB"
Thoughts:
 relevance: 5
 reviewed: false
---
# Historia de las bases de datos

Una base de datos se considera como una colección organizada de datos (Beynon-Davies,
2014), según esta definición, la historia de las bases de datos podría haberse iniciado con
la aparición de las tarjetas perforadas, las cuales sirvieron para almacenar información.
A partir de 1725 hasta la actualidad, la cronología de hechos resaltantes sobre el
almacenamiento de información, sería la siguiente:

## Hechos
- **Hecho 1** - En 1790, el francés Joseph Marie Jacquard inventó la Máquina de Jacquard para la
industria textil, “He first turned his attention to the machine which now bears his name
in 1790. At first he did not succed, but in 1801, he has completed it and it was exhibited
in the National Exposition, Paris, when he received the reward of a bronze medal for
the invention” (Barlow, 1878, p.140). La máquina de Jacquard almacenaba la
información que contenía el diseño gráfico de los telares en tarjetas perforadas. El
mismo autor indica que en 1725, M. Bonchon empleó la tarjeta perforada: “M.
Bonchon, in 1725, employed a band of pierced paper” (Barlow, 1878, p. 141). El
estadounidense Herman Hollerith aplicó electricidad al principio del telar de Jacquard
(Austrian, 1982).
- **Hecho 2** -  En 1911, la compañía de máquinas tabuladoras de Hollerith se fusionó con las
compañías: Computing Scale Company of America e Internactional Time Recording
Company. Esta empresa combinada de Computación Tabulación y Registro (CTR),
comenzó a fabricar, entre otros, tarjetas perforadas (International Business Machines
Co., Limited, 2020).
- **Hecho 3** - En 1917, la compañía CTR se convierte en la IBM (International Business Machines
Co., Limited, 2020).
- **Hecho 4** - En 1957, la IBM lidera el procesamiento de datos con el Método de Contabilidad y
Control de Acceso Aleatorio IBM 305 (RAMAC) (International Business Machines
Co., Limited, 2020).
- **Hecho 5** - En 1963, Charles W. Bachman se convierte en el pionero en la administración de bases
de datos. Su software Integrated Data Store permitía compartir datos entre diversas
aplicaciones (Lohr, 2017).
- **Hecho 6** - Entre 1960 y 1980, el inglés Edgar Frank Codd permitió el inicio de la industria de las
bases de datos relacionales, “the man who, singlehanded, put the field of database
management on a solid scientific footing” (ACM, 2020). En este mismo periodo
aparece el lenguaje estructurado de consultas (SQL) como uno de los pilares
fundamentales de la arquitectura de las bases de datos modernas (Chapple, 2020).
- **Hecho 7** - En 1983, los modelos de bases de datos orientados a objetos empezaron a utilizarse
ampliamente desde 1983 (Bertino & Martino, 1995, p. 13). “La clave de la
programación orientada a objetos es considerar a un programa como si estuviera
compuesto de objetos independientes, agrupados en clases, los cuales se comunican con
otros objetos por medio de mensajes” (Bertino & Martino, 1995, p. 13).
- **Hecho 8** - En 1990, se comienza con la explotación de las bases de conocimiento (Frawley,
Piatetsky-Shapiro, & Matheus, 2020), aparece “la Minería de Datos que se ocupa de
descubrir patrones de datos ocultos y no esperados desde grandes bases de datos”
(Beynon-Davies, 2014, p.604) .
- **Hecho 9** - En 1997, se utiliza por primera vez el término “Big Data”, como el procesamiento de
una cantidad ingente de datos masivos, tanto que no puede ser procesada por la
tecnología ni software convencional (Ideas para tu empresa, 2020). Big Data es la más
reciente evolución de las bases de datos que, administra inmensos volúmenes de
información almacenada en múltiples formatos (texto, imágenes y vídeo) y además, la
procesa a grandes velocidades para satisfacer los requerimientos de las empresas de hoy
en día.
- **Hecho 10** - En 2020, según (Kroenke et al, 2020) las aplicaciones Web, las aplicaciones de
smartphone y las aplicaciones de IoT, dependen de las bases de datos.

## Arquitectura de las bases de datos

La arquitectura de tres niveles de las bases de datos responde positivamente a las
exigencias de independencia, flexibilidad y capacidad de evolución de la base de datos
(De Miguel & Piattini, 1997, p. 65). El esquema conceptual permite la independencia
del usuario con el nivel físico (De Miguel & Piattini, 1997, p. 62). Asimismo, el
esquema conceptual se puede transformar según la dinámica de la información en la
empresa. Además, se pueden introducir cambios en el esquema interno, para la
adaptación a nuevas circunstancias de la empresa (De Miguel & Piattini, 1997, p. 65).
como se ve en la Figura 1.

### Figura1: Los tres niveles de abstracción de los datos y la arquitectura
triesquemática de ANSI
![AbstracionDeDatos](https://res.cloudinary.com/dffa1tukw/image/upload/v1663018830/2022-09-05-00-23-campus.uandina.edu.pe_lrwl14.png)


## Modelos de bases de datos más utilizados

Siendo una base de datos, una colección organizada de datos (Beynon-Davies, 2014)
y un modelo, la representación en pequeño de alguna cosa (Asociación de academias
de la lengua española, 2020), el modelo de una base de datos es la representación de
una colección organizada de datos de una empresa, o de cualquier parte del mundo
real. “La función de la base de datos es almacenar toda la información necesaria para
la empresa (o para la parte del mundo real elegida para modelar) de forma
centralizada, eliminando así la información redundante dentro de la misma” (Jackson,
1990, p. 1). Los modelos de bases de datos más conocidos son: El modelo entidad -
relación y el modelo orientado a objetos.

### El Modelo Entidad – Relación

“Una base datos relacional no es más que un conjunto de relaciones que
contienen la información almacenada en la base de datos” (Jackson, 1990, p. 5)
Se establecen asociaciones entre las diferentes entidades que se encuentran en esa
parte del mundo real que se va a modelar.
Las bases de datos relacionales son las más populares en el comercio y en la
industria (Beynon-Davies, 2014, p. 98).
El modelo Entidad – Relación es el más popular en el mundo (Kroenke et al,
2020).

### El Modelo Orientado a Objetos

En el modelo orientado a objetos, las entidades que conforman la base de datos
relacional, pasan a llamarse clases de objetos y, el modelo orientado a objetos es
un esquema que representa asociaciones entre estas clases de objetos (Bertino &
Martino, 1995, p. 34).