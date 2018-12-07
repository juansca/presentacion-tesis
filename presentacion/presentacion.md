# Introducción

Hola, hoy les voy a presentar mi trabajo final de la licenciatura en Cs de la compu.
Antes que nada, queria aclarar que fue un trabajo que se desarrolló de una manera
fuertemente interdisciplinaria en conjunto con personas de conae y con colaboración
de miembro de la Organización mundo sano.
Es por ello y por mi visión de la profesión que esta presentación va a estar
enfocada a ello. La idea es que todos los que están presentes puedan entender
la mayor parte del trabajo y de los resultados obtenidos.


# Motivacion
A mi entender, todo trabajo y proyecto debe estar empujado por una motivación la
cual luego nos permite generar explícitamente el conjunto de objetivos que
tendrá asociado el mismo. Así que arranquemos por ahí


En este trabajo existen, al menos, dos grandes motivaciones. Una que tiene
que ver con la problemática epidemiológica y el impacto de los resultados en ese
aspecto y la otra con el aporte que se puede generar en la comunidad de
profesionales que abordan estas problemáticas
Las otras van por el lado del crecimiento personal y profesional que genera
participar de este tipo de proyectos.

## Mosquito y enfermedad
Desde el punto de vista de la problemática epidemiológica podemos mencionar
varias cuestiones que la hacen surgir.

Por un lado, se sabe que el mosquito es uno de los vectores de enfermedades humanas
más importantes en el mundo. En particular, el Aedes aegypti es el principal vector
de Dengue, Chikungunya, Zika y Fiebre Amarilla urbana.

A su vez, según datos de la Organización Mundial de la Salud (OMS),
alrededor de 80 millones de personas se infectan de Dengue anualmente, cerca de 550
mil enfermos requieren hospitalización y unos 20 mil mueren.
2.500 millones de personas corren riesgo de contraer la enfermedad y más de 100 paı́ses tienen transmisión endémica



- Aquí podemos observar un mapa de la Argentina que nos muestra el índice
de enfermos de Dengue cada 100mil habitantes, a nivel provincia. Aquí,
se tienen en cuenta los casos confirmados y probables hasta la semana número 20
del año 2016

- Mostrar alguito -

Sumado a lo comentado, por su parte, el Aedes aegypti se caracteriza
por su:
  Gran capacidad adaptativa
  Resistencia a insecticidas
  Resistencia de huevos a la desecación
  Presencia en el medio urbano
  Preferencia de cria en contenedores artificiales




En términos del aporte a los profesionales que trabajan actualmente, resulta
interesante saber cómo lo están haciendo.

La tendencia y actualidad es utilizar información satelital para generar los
modelos dado que de esa manera se puede obtener información ambiental
con alcance regional, tiene características espacio-temporales. Ésta, tuvo
grandes avances en los últimos años. Aunque actualmente, los modelos que se
utilizan asumen relaciones lineales entre las variables en cuestion.


Ahora, recapitulando. Hablemos de algunas cuestiones a tener en cuenta.
Por lo que ya les comenté, es claro que la prevención de estas enfermedades
transmitidas por vectores debería ser, a través del control de
vectores


- Dado que la cantidad de vectores, el virus circulante y
la susceptibilidad humana dependen directa o indirectamente de variables climáticas y am-
bientales tales como la temperatura, la lluvia, la vegetación, entre otras, el cambio climático
es, también, un factor de riesgo para el desarrollo de las enfermedades en cuestión.


Ésto deriva en la necesidad de enfocar esfuerzos en el desarrollo de estrategias
contundentes dirigidas a evitar, limitar y controlar las poblaciones de Aedes aegyti, lo que
implica repensar y diseñar nuevos sistemas de alerta temprana, vigilancia epidemiológica

## Hasta ahora qué hacen

- El uso de información satelital se ha estado utilizando desde hace algunos años, como
uno de los métodos para atacar el problema mencionado. Ésta técnica permite modelar la
evolución temporal y geográfica de las poblaciones del vector utilizando variables ambientales
obtenidas de los sensores remotos.

- Aunque hasta ahora, estos trabajos utilizaban fuertes
asunciones al utilizar modelos lineales para relacionar las distintas variables, y por más
que los resultados obtenidos hasta el momento han sido favorables, no existen resultados que
prueben el hecho de que las relaciones que se establecen entre el desarrollo del mosquito y las
variables ambientales del entorno son de tipo lineal.

- Esto nos permite generar la hipótesis de
que modelos no-lineales son capaces de modelar relaciones que se adapten mejor a la realidad.


## Approach a los objetivos

- Desarrollar un modelo de aprendizaje automático puede resultar extremadamente com-
plejo y costoso en términos computacionales y de experiencia de quien lo lleve a cabo

- A su vez, también existe el importante problema de la escases de datos de campo para
utilizarlos en la construcción de los modelos. Hasta ahora, era un gran limitante ya que no se
tienen datos vitales para el desarrollo de este tipo de herramientas.


# Objetivos

Los objetivos de este trabajo apuntan a aportar conocimientos y herramientas a los
profesionales dedicados al desarrollo de sistemas de prevención y mitigación del Dengue, Zika,
Chikungunya y enfermedades vectoriales en general.


- Implementación de una herramienta para la generación de nuevos modelos predictivos
a partir de variables ambientales. Dadas las caracterı́sticas interdisciplinarias de la pro-
blemática en la epidemiologı́a, dicha herramienta debe ser utilizable por profesionales
que no sean expertos en informática o en aprendizaje automático.

- Validar la hipótesis de que modelos no-lineales son mejores para predecir y ajustar la
oviposición de mosquitos que los modelos lineales utilizados hasta el momento.


- Proponer una solución a la problemática de la escases de puntos con datos de campo
para entrenar los modelos




# Marco Teorico


- La Teledetección se define como el proceso de adquirir información acerca de un objeto,
área o fenómeno desde la distancia. Un sensor remoto es un instrumento capaz de realizar
percepción remota, por lo que en esta amplia definición caben desde los ojos hasta los
radiotelescopios.


- A su vez, la información obtenida por dichos SR se puede aplicar a estudios en-
tomológicos 2 , debido a que ellos proveen gran cantidad y diversidad de información sobre la
cobertura de la Tierra: caracterı́sticas de la vegetación, cuerpos de agua, temperaturas, entre
otras.

- Ésta, también es información sobre el hábitat de insectos y artrópodos vectores [8,22],

- y, por lo tanto, de acuerdo a la teorı́a de Pavlovsky [63] en la que expone la correlación entre
el hábitat y enfermedades transmitidas por vectores, los datos de los SR se pueden utilizar
como fuente de información sobre la distribución espacio-temporal de dichas afecciones.



- Las condiciones ambientales que determinan la conectividad 5 de los paisajes para la
disperción pueden variar en las distintas regiones y dependen de cómo el patógeno se dispersa

- figura  de propagacion y conectividad

- biológicamente (e.j: dado un patógeno portado por vectores, el movimiento del insecto) o
abióticamente (e.j: flujos de viento o agua).


- Ecologı́a Panorámica, una ciencia con inicios en los años 1930s que
se dedica a estudiar las interacciones entre los ambientes y la vegetación.

-  En simultáneo con el nacimiento de la
ecologı́a panorámica como una ciencia, Pavlosky estipula el concepto de nidalidad 8 (o foca-
lidad) de las enfermedades, donde los patógenos son asociados a paisajes (zonas) especı́ficos.

1. Vectores con capacidad de transmisión de la infección
2. Vertebrados capaces de funcionar como reservorio de la infección
3. Huéspedes susceptibles, como humanos o animales domésticos


- El concepto de focalidad mezclado con la ecologı́a panorámica llevó al nacimiento de la
ciencia contemporánea Epidemiologı́a Panorámica, en la cual las enfermedades pueden
ser asociadas a distintas caracterı́sticas del paisaje o cómo la configuración entre el vector,
el huésped y el patógeno se intersecan dado un clima permisivo para que ello suceda.
