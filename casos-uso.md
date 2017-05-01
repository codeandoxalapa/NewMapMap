CASOS DE USO MAPMAP 	
===================
// revisar coerencia y ortografia en en todo el doc
**Resumen:** este artículo presenta los casos de uso
desarrollados en una aplicación para el aprendizaje móvil denominada MapMap, desarrollado en colaboración
con la comunidad de ** Codeando Xalapa,Xalapa JS y estudiantes de la Universidad Veracruzana.**

la cual permite que usuarios de dispositivos móviles de sistema operativo Android,puedan recolectar
información de rutas de transporte en formato GTFS.
Se documenta un ejemplo de caso de uso,
especificaciones de requisitos, diseño de interfases
basadas en los patrones de Android, para permitir la
comunicación y el uso.

// FALTA COMPLEMENTAR Y REVISAR LO QUE YA SE HA ESCRITO EN LA PARTE DE ARRIBA PARA SU APROVACION 

Introducción	
============================
// buscar . pregguntar la descripcion de lo que hace la aplicacion de una manera mas detallada y que no sea muy geeneral 

Considerando lo vital que es la gestión de requisitos y lo útiles que son los casos de uso, nunca esta de más intentar una explicación de la técnica. para lo cual se hace esté caso de uso para la aplicaicon MapMap.En dicha aplicación, es de interés realizar el trasado de rutas del transporte público de la ciudad de xalapa , o en otras palabras, la aplicación se encarga de "dibujar" el trayecto que realiza el servicio urbano de un punto A hacia un punto B. 

Descipción
=============
Aplicación open source que permite trazar rutas de transporte público para poder recolectar información en formato de dato abierto y así crear GTFS feeds.

// falta realziar al descripcion de la aplicacion mas detallada 
 
Identificacion del actor 
=======================

Primero hemos de identificar al actor. En este caso es claramente el usuario del teléfono movil o **"mapeadores de ruta"**.
Ahora identificaremos cuales  son las actividades precisas que queremos expresar en nuestro modelo.Estamos hablando desde **como se instala la aplicación en Android o ios,los primeros pasos ya dentro de la aplicacion desde: trazar(ruta),recorridos y enviar ** . Así como las indicaciones para el buen trazado de ruta.

//se comenzará desde que el usuario desea  instalar la aplicación en su dispositivo android  postriormente sera el caso para //ios para  ser un mapeador o trazador de rutas.
Armados con estos datos, podemos construir una tabla que resuma lo que tenemos en nuestro caso de uso:
Nombre caso de uso: isntalación de la aplicacion 
actores: usuario 
descripcion :  el usuario descargara e instalara la aplicacion en su telefono movil para despues realiara el  trazo de la ruta correspondiente donde el usuario conocera todas las funciones de la aplicacion mediante este caso de uso.

INSTALAR APLICACION
============================
**Obtén MapMap desde Google Play Store**
======================================================
**Cómo buscar y descargar MapMap** 
   **instalacion paso a paso**

//  VER SI ES CONVENIENTE LA EXPLICACION PASO A PASO 
// para mi no lo veo conveniente pues ya con las imagenes seria mas entendido 

> - 1.- Abre la app de Google Play Store Play Store.
	Nota: También puedes acceder desde play.google.com.

> - 2.- Ir a la barra de busqueda de plays store. 
	Escribe en el rectangulo de busqueda---> codeando xalapa ya escrito aparecera el icono de la aplicacion de MapMap. 
	Nota: lo ideal seria escribir MApMAp pero habria un poco de inconveniente porque en los resultados de busqueda nos apareceran mas aplicaciones de diferentes desarrolladores pero para una busqueda mas efectiba 
	se recomienda escribir codeando xalapa porque solo aparecera uun resultado de busqueda.

> - 3.- tienes dos opciones de instalacion 
	**Opcion 1 :** selecciona los 3 puntos que esta al lado derecho de la aplicacion y selecciona instalar 
	hora aparece un pequeño recuadro con un boton verde que dice ACEPTAR  selecciona ese boton
	la aplicaion ya se estara instalando en tu dispositivo. 
 	**Opcion 2 :** selecciona la aplicacion ahora aparecera un boton verde del lado derecho  que dice INSTALAR seleccionalo ahora aparece un pequeño recuadro   con un boton verde que dice ACEPTAR  selecciona ese boton la aplicaion ya se estara instalando en tu dispositivo. 
// las screenshots creo para ahorrar espacio las podria recortar y poner solo lo necesario 
// esto para abarcar mucho espacio 


// mi otra duda es que tan extenso tiene que hacerse el caso de uso 
// o eso no tiene nada que ver?? osea que no importa el tamaño ??? 	  

Instalacion rapida
=======================
> - Abre la app de Google Play Store Play Store.
<a href="http://es.tinypic.com?ref=2i1fudy" target="_blank"><img src="http://i68.tinypic.com/2i1fudy.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
> - Busca codeando xalapa. 
> - Selecciona  la aplicacion MapMap.
<a href="http://es.tinypic.com?ref=15p63km" target="_blank"><img src="http://i68.tinypic.com/15p63km.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
> - ahora sigue las instrucciones en pantalla para instalar la aplicacion 
<a href="http://es.tinypic.com?ref=30aza0o" target="_blank"><img src="http://i64.tinypic.com/30aza0o.jpg" border="0" alt="Image and video hosting by TinyPic"></a>
<a href="http://es.tinypic.com?ref=28apbo3" target="_blank"><img src="http://i64.tinypic.com/28apbo3.jpg" border="0" alt="Image and video hosting by TinyPic"></a>

> - la aplicacion ya esta instalada en tu dispositivo. 
<a href="http://es.tinypic.com?ref=5duhde" target="_blank"><img src="http://i63.tinypic.com/5duhde.jpg" border="0" alt="Image and video hosting by TinyPic"></a>

// necesito saber si asi tego que seguir hacienso cada caso este fue el caso para la instalacion 
pero imagino que tengo que hacerlo para cada caso en la aplicacion 
































