# Caso de Estudio: Fedex

El objetivo de este trabajo consiste en buscar un/unos datasets que puedan en conjunto con sus datos, brindar la posibilidad de proyectar cuáles serán los puntos más eficaces en donde la empresa de encomienda debería instalar sus nuevas sucursales para el año 2030.

La empresa seleccionada fue Fedex, que pertenece al rubro de logística internacional, el cual​​ ofrece servicios de mensajería, entrega de paquetes y correo urgente. El propósito de la compañía es proporcionar una cadena de logística segura y que el paquete llegue en el tiempo, formato y condiciones acordadas.

En primer lugar acudimos a la página Kaggle para poder encontrar el dataset o la combinación de datasets más eficaz. Las variables seleccionadas fueron el crecimiento poblacional y el crecimiento del PBI. Como se mencionó anteriormente, nuestra intención es determinar cuál sería el país óptimo para colocar una sede nueva, en base a el crecimiento del mercado por la variable de cantidad de personas en el mismo y generación de recursos (dinero en la economía).

Una vez obtenidos los datasets, se debió subir los mismos al Visual Studio, para después unirlos y por último limpiarlos (este último paso consistió en examinar los datasets, para así de ese modo, ver la existencia de posibles valores nulos, esto concluyó con la eliminación de columnas correspondientes a los años anteriores al 2000, así como también del 2020 por ausencia de datos). Debido a esto, los años a analizar son del 2000 al 2019.

A continuación, se debió utilizar la función merge para los datasets por el country code, se eliminaron columnas repetidas y se cambió el nombre.

Luego, se dio entablar la correlación de los datos, lo cual consiste en la medición de dos variables y la relación que tienen las mismas entre sí. Cuando existe una alta correlación entre dos variables, estas demuestran estar ligadas y por ende dependen mutuamente de sí mismas. Básicamente, cuando una se ve afectada, la otra reacciona al cambio de la variable que cambió.

Al momento de hacer la correlación de nuestros datos con las variables fijadas, se notó una baja correlación entre las variables, por lo cual indicaría que el PBI no está correlacionado al crecimiento poblacional de un país. Dado que, no nos parece una medida coherente para proyectar un país óptimo al cual colocar la sede de Fedex. 
Esto puede darse por varios motivos, puede que el crecimiento este rezagado en base a el crecimiento económico y que se dé a los años de un incremento en el PBI. A su vez, otro de los motivos que pueden verse, es que los países siempre crecen en población, pero su PBI aumenta o disminuye por factores externos a ellos, o simplemente la población no afecta en sí al PBI del país de manera. 

Posteriormente, se llevó a cabo la regresión lineal, éste es un método en el cual se aplica un modelo para formar una ecuación en base a los datos que uno tiene de sus variables. Esta se relaciona con la correlación, dado que a mayor correlación, habrá menos dispersión (distancia a la cual se alejan los distintos puntos de la línea de la ecuación) entre los datos obtenidos y la ecuación formulada. 

Más allá de los datos, uno no puede determinar el bienestar de un país a largo plazo en el estado que probó estar el mundo en los últimos 5 años. Hemos visto una pandemia que dejó parado y estancado a varios países, una guerra que cambió la dinámica del comercio y la energía en Europa y una crisis inflacionaria que preocupa a los países que demostraron ser más confiables y estables en el mundo y que ahora cursan una recesión. Por lo que aunque uno pueda estimar la supuesta posición de un país, en la eventual situación que el mundo se mantenga estable, sería muy difícil prever todas las posibles desestabilizaciones que ocurran en el camino o que pasen a la hora de abrir una nueva sede.

Como conclusión, no llegamos a un modelo para poder determinar con nuestros datos un país al cual hacer una sede para el 2030. Nos parece que se necesitan variables adicionales para lograr formular un modelo el cual pueda predecir mejor el mercado para el 2030, los cuales no fuimos capaces de incorporar por nuestra cuenta. 
