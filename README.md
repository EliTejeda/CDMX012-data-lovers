# Proyecto Data Lovers - Dex-Rick & Morty

## Índice 
* [1. Definición del producto](#1-definici%C3%B3n-del-producto)
* [2. Historias de usuario](#2-historias-de-usuario)
* [3. Prototipo de baja fidelidad](#3-prototipo-de-baja-fidelidad)
* [4. Prototipo de alta fidelidad](#4-prototipo-de-alta-fidelidad)
* [5. Testeos de usabilidad](#5-testeos-de-usabilidad)

***

## 1. Definición del producto
Nuestro proyecto se desarrolló a partir de la data de “Rick & Morty” serie animada americana dirigida a niños y adultos. Por su temática encontramos muy interesante el hecho de ser un fandom (18-35 años aprox.) que en su mayoría apela a cierta nostalgia a los juegos, películas y series retro, es por ello muy importante para nosotras darle a la web ese estilo muy característico.
Además de la información proporcionada sobre los usuarios, decidimos realizar un [formulario](https://es.surveymonkey.com/r/XX37JZW) para conocer algunas de las preferencias del fandom del a serie, principalmente enfocado en las necesidades de usabilidad e interacción del usuario con la interfaz (UX).



## 2. Historias de usuario

Parte fundamental para definir el proyecto fue encontrar eso puntos necesarios a cubrir que arroja la encuesta y como podíamos utilizarlo en conjunto con la data proporcionada, por lo que podemos encontrar las siguientes historias a cubrir:

### Historia de Usuario 1
**Yo como usuari@ de Rick & Morty, quiero entrar al mundo de la serie y visualizar los personajes para conocerlos**

#### Criterios de Aceptación
* Diseñar una página con un estilo característico de la serie agregando un toque retro ochentero espacial alusión a una de interfaz de videojuegos.
* Debe ser visualmente atractivo y divertido muy colorido como la serie.
* El usuario debe poder navegar de forma sencilla e intuitiva. 
* Diseñar una segunda página que aloje a los personajes en tarjetas que contegan los datos e imagen del personaje y diferentes botones para el filtrado de información y datos curiosos.

#### Definición de terminado
* Realizar prototipos LOW del diseño de interfaz sugiriendo los módulos que contendría y el recorrido de navegación de las páginas.
* Crear el repositorio principal y ramas para trabajar y poder realizar los cambios en las respectivas ramas del equipo de trabajo, Github.
* Fusionar ideas y crear prototipos de alta en Figma.
* Recibir feedback del prototipo.

### Historia de Usuario 2
**Yo como usuari@ de Rick & Morty quiero conocer datos característicos de los personajes con su imagen y poder buscarlos de diferentes formas**

#### Criterios de Aceptación
* Se muestra página principal del portal y al dar click el usuario accede a la página de tarjetas de personajes.
* Se muestran las tarjetas de los personajes con imagen e información.
* El usuario puede elegir entre diferentes filtros para buscar la información. 
* El diseño de la página es intuitivo y fácil de usar.
#### Definición de terminado
* Todas las paginas cuentan con los fondos definidos, el titulo de Rick&Morty en .png, armado de esqueleto html y diseño CSS.
* La página principal incluye el gif del portal que a su vez es el botón de entrada, armado de esqueleto html y diseño CSS.
* En la segunda página se muestra la data filtrada dentro de contenedores en un grid y se trabaja en CSS con el diseño de los correspondientes módulos flexbox.
* Podemos ver un filtrado aun en botón sencillo de A-Z verificando que la acción se cumpla, main.js, data.js.

### Historia de Usuario 3
**Yo como usuari@ de Data Lovers quiero filtrar la informacion de A-Z, de Z-A, Male, Female, Specie, Top10 y que numero de personajes son mujeres**

#### Criterios de Aceptación
* El usuario puede elegir diferentes filtros para buscar la información 
* Las tarjetas de los personajes se encuentran centradas y cuentan con la informacion e imagen de cada personaje.
* La pagina cuenta con una barra horizontal en la parte de arriba con las opciones de los diferentes filtrados.
* La pagina cuenta con secciones laterales con informacion adicional.
* La pagina cuenta con una sección que muestra una grafica del top10 de personajes que mas vemos en la serie.
* La página cuenta con 

#### Definición de terminado
* 

### Historia de Usuario 4
**Yo como usuari@ de Data Lovers quiero crear una pagina responsiva pensando en la usabilidad del usuario y generar la mejor experiencia del usuario**

#### Criterios de Aceptación
* El usuario puede filtrar y ordenar por personajes y estos se muestran en la pantalla.
* Cuando se aplique el filtro, los personajes se pueden ordenar bajo diferentes criterios.
* Es visualmente atractivo y fácil de usar.

#### Definición de terminado
* Agregar al menú de filtrado de la data, la opción de filtrar por "personajes" y que estos se muestren en la pantalla.
* Crear nuevos criterios de ordenamiento de la información como: alfabéticamente y por edad.
* Haber solicitado feedback del prototipo.
* El código de las programadoras debe estar integrado en GitHub a través de un PR (pull request).
* Haber escrito el test de la(s) función(es) utilizadas.

## 3. Prototipo de baja fidelidad
Los prototipos realizados en esta etapa del proyecto se hicieron basados en la información que teniamos recabada, el primero era un acercamiento a las ideas mas locas que se nos podian ocurrir y el segundo ya un poco más aterrizado a las secciones que contendria la página. 
![Prototipo Low 1](/src/assets/prototipoLow1.jpeg)
![Prototipo Low 2](/src/assets/prototipoLow2.jpeg)

## 4. Prototipo de alta fidelidad
Continuando con la idea de secciones de los bocetos anteriores se trabajo en un [prototipo de alta fidelidad](https://www.figma.com/proto/7SYhVZosKhp56iL0cTP1pe/Dex-Rick-and-Morty?node-id=11%3A7&scaling=contain&page-id=0%3A1&starting-point-node-id=11%3A7&show-proto-sidebar=1) en Figma. 

Siguiendo los diferentes feedbacks de usuarios decidimos simplificar el diseño, aunque procuramos ser muy fieles al diseño original, decidimos eliminar las diversas secciónes y solo quedarnos con la página de incio y la segunda página de información esto para que la usabilidad fuera menos compleja y llegar más directo a la información.
En vez de la seccion que contenia los botones de navegación cambiamos por una barra en parte superiro que contuviera los botones y filtros

## 5. Testeos de usabilidad
Esta parte fue escencial y en todo el proceso nos tuvimos que detener un momento y cuestionarnos si era correcto el rumbo que tomaba nuestra página, por lo que se hicieron los siguientes cambios:

* La idea inicial contaba con varias paginas para navegar dependiendo de la información que querías buscar, los usuarios indicaron que buscaban acceder de una forma mas sencilla a la información.
* En un principio se penso en deslizado de imagenes, en el feedback se nos sugirio presentar las tarjetas de manera sencilla pero visualmente atractiva. 
* 