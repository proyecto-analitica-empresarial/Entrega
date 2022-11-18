Caso de Estudio: Fedex

El objetivo de este trabajo consiste en buscar un/unos datasets que puedan en conjunto con sus datos, brindar la posibilidad de proyectar cuáles serán los puntos más eficaces en donde la empresa de encomienda debería instalar sus nuevas sucursales para el año 2030.

La empresa seleccionada fue Fedex, que pertenece al rubro de logística internacional, el cual​​ ofrece servicios de mensajería, entrega de paquetes y correo urgente. El propósito de la compañía es proporcionar una cadena de logística segura y que el paquete llegue en el tiempo, formato y condiciones acordadas.

En primer lugar acudimos a la página Kaggle para poder encontrar el dataset o la combinación de datasets más eficaz. Las variables seleccionadas fueron el crecimiento poblacional y el crecimiento del PBI. Como se mencionó anteriormente, nuestra intención es determinar cuál sería el país óptimo para colocar una sede nueva, en base a el crecimiento del mercado por la variable de cantidad de personas en el mismo y generación de recursos (dinero en la economía).

Una vez obtenidos los datasets, se debió subir los mismos al Visual Studio, para después unirlos y por último limpiarlos (este último paso consistió en examinar los datasets, para así de ese modo, ver la existencia de posibles valores nulos, esto concluyó con la eliminación de columnas correspondientes a los años anteriores al 2000, así como también del 2020 por ausencia de datos). Debido a esto, los años a analizar son del 2000 al 2019.

A continuación, se debió utilizar la función merge para los datasets por el country code, se eliminaron columnas repetidas y se cambió el nombre.

Luego, se dio entablar la correlación de los datos, lo cual consiste en la medición de dos variables y la relación que tienen las mismas entre sí. Cuando existe una alta correlación entre dos variables, estas demuestran estar ligadas y por ende dependen mutuamente de sí mismas. Básicamente, cuando una se ve afectada, la otra reacciona al cambio de la variable que cambió.

Al momento de hacer la correlación de nuestros datos con las variables fijadas, se notó una baja correlación entre las variables, por lo cual indicaría que el PBI no está correlacionado al crecimiento poblacional de un país. Dado que, no nos parece una medida coherente para proyectar un país óptimo al cual colocar la sede de Fedex. 
Esto puede darse por varios motivos, puede que el crecimiento este rezagado en base a el crecimiento económico y que se dé a los años de un incremento en el PBI. A su vez, otro de los motivos que pueden verse, es que los países siempre crecen en población, pero su PBI aumenta o disminuye por factores externos a ellos, o simplemente la población no afecta en sí al PBI del país de manera. 

Esta misma correlación dio un resultado de 0,14, al ser tan baja, no se consideró apropiado ejecutar una regresión de GDP en función de la población (ya que de lo contrario se debería llevar a cabo para todos los países). Por lo que, se realizó una autorregresión, la cual devuelve una variable en sí misma.

Prosiguiendo con el análisis, se ensamblaron los datasets, a su vez, para cada uno de los datos, se efectuó una media del crecimiento del país, primero en población y segundo por PBI. Después se realizó el top 25 con mayor crecimiento de cada uno de éstos y dio como consecuencia a aquellos países que poseían los valores más elevados en relación al PBI y  población.

A modo de conclusión del trabajo, es posible afirmar que los tres países con que poseían la mayor recepción de una sucursal de Fedex son Uganda, Chad y Guinea Ecuatorial, si bien estos tres, no son países con un nivel de desarrollo tan atroz como el de muchos países europeos, tiene sentido que tengan mayor potencial de crecimiento que países que ya lo son, o por el otro lado, que sean paises mas atractivos para instalar nuevos negocios debido a su ubicación geográfica cercana a Europa y Asia, a diferencia de otros países en vía de desarrollo que poseen la desventaja de no encontrarse cercanos a potencias Europeas o Asiáticas.



Bibliografía: Presentaciones del Curso.
