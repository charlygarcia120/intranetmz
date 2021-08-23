# intranetmz.tripod.com
## Bitacora de mejoras y actualizaciones al sitio web de la intranet de Manizales.

Contenidos
Los contenidos de la intranet de Manizales son conseguidos y/o elaborados de diversas fuentes principalmente
Sitios web personales
Libros y Bancos de datos
Aportes personales
Fotografias tomadas por el quipo de edición de contenidos
Fotografias encontradas en la red
Material Aportado por las personas del equipo de edición
Aportes de Nuestros visitantes (Inmuebles y Clasificados)


Informática
La intranet de Manizales ha sido desarrollada usando herramientas de software libre,Principalmente 
- CGI (perl 5) como lenguaje de programacion (GNU)
- bases de datos libres
- Javascript en la tecnologia de programacion del lado cliente
  - jquery
  - jsgrid
  - dhtmlx
-Hojas de estilos en Cascada (CSS)

## Bitacora


### 5 Junio 2006: 
se creo el sitio web http://intranetmz.tripod.com e una cuenta de free hosting de tripod.com y se creo un index.html con la descripcion basica del sitio web

### 5 Agosto 2006: 
Se agregaron los barrios y comunas de Manizales al sitio web  https://tinyurl.com/yky2l4gk

### 8 Marzo 2008: 
Se creo un programa en PERL para la generacion del sitio web de las comunas de Manizales, genera documentos HTML para cada comuna y barrio https://intranetmz.tripod.com/comunas_manizales/

### 13 Junio 2009: 
Se creo un programa en PERL para la generacion de la publicidad de sitio web de empresas de manizales para ubicar en el lado izquierdo del sitio web. se sincroniza con un generador de shots para sitios web  https://intranetmz.tripod.com/cgi-bin/publimani.cgi y asi se saca un minisitio web uo un pantallazo de los sitios web que desean estar pautados o con su enlace en la intranet de Manizales.

### 23 Marzo 2010: 
Se creo el blog de manizales como un sitio repositorio de contenido y de apoyo a la intranet de Manizales, el blog tiene la posilibidad de usar la infraestructura de google para poder  aumentar la cantidad de contenido sin incrementar costos, y maximizando la encontrabilidad de nuestra link Whell en los buscadores . El blog de Manizales ha sido creado en esta fecha en la siguiente direccion , inaugurandose con una entrada sobre , el parque caldas manizales : http://sobremanizales.blogspot.com/2010/03/una-caminadita-por-el-parque-caldas.html

### 1 Junio 2010: 
Se implemento el Algoritmo de shuffle en PERL para barajar los elementos de los registros a mostrar pero de una manera "barajada" , tanbien es llamado el algoritmo de Fisher Yates  https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle 


### 8 Julio 2011: 
Se creo un programa en PERL para la generacion de puntos con localizaciones  de comunas y barrios de Manizales, busqueda con filtros de esos puntos.


### 21 Marzo 2012: 
Se implemento el Algoritmo de montoEscrito (https://tulengua.es/numeros-texto/) convertir de numeros a texto para permitir la conversion del precio de los inmuebles agregados por nuestros visitantes y usuarios: ejm (Precio: $75000000= Convierta :setenta y cinco millones de pesos) ejemplo en el sitio web:  https://tinyurl.com/yntwx5du


### 26 Marzo 2012: 
Se implemento el Algoritmo de envio de datos desde la pagina al buscador de google para la conversion de el precio de inmuebles registrados por los usuarios de pesos colombianos a dolares, yenes, y euros y GBPs https://tinyurl.com/yntwx5du


### 18 Enero 2021: 
Se agrega la matriz de sitios turisticos de Manizales usando JQuery en el documento inicial del sitio web: http://intranetmz.tripod.com diferente para cada vez que se carga el documento HTML con enlaces hacia los segmentos interiores del sitio web relativos a cada sitio turistico

### 5 febrero 2021 
Se desarrollo el algoritmo de categorias de sitios turisticos usando tablas y JsGrid creando botones que al presionarlos muestran la informacion solicitada en alguna area de la pagina web, mas especificamente en la columna central: https://intranetmz.tripod.com/cgi-bin/intranetmz/sitios_turisticos.cgi

### 13 Marzo 2021: 
Se creo un programa para el tratamiento estadistico de los resultados de la loteria de Manizales, y se hace un analisis de las probabilidades con los numeros que menos salen en cada cifra para reocmendar paras , es solo un ejercicio de probabilidad y estadistica aplicado a series de 4 cifras http://intranetmz.tripod.com/cgi-bin/intranetmz/pronostico_loteria.cgi

### 16 Marzo 2021: 
Se actualizaron las consultas sobre los sitios consultas, usando AJAX y JQuery, para cambiar los contenidos del area central dependiendo del sitio turistico que
el usuario seleccione.

### 24 Marzo 2021: 
Se integraron reportes graficos al programa para pronostico estadistico de la loteria de Manizales, utilizando Charts para las cifras y pasteles para la serie del premio mayor, se hacen los graficos usando Javascript. https://bit.ly/3faPSmj

### 16 Julio 2021: 
Se hace una mejora al programa de pronostico de loteria de manizales para que solo visualize este pronostico los dias miercoles. Tambien se elimina la opcion de segujimiento de contador de visitas por cuestion de tamaño de los arhcivos planos para cada mes

### 30 Julio 2021: 
Se cambia el tabbar de la pagina principal se remplaza el componente de dhtmlx por el tabbar jquery UI.

### 4 Agosto 2021: 
Se optimizan los archivos CGI para eliminar acceso a datos en archivos planos y que sea mas rapido el sitio web al usar menos archivos de configuracion para los programas CGI. 

