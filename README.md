<div style="width: 1000%; clear: both;">
<div style="float: left; width: 50%;">
<img src="https://trabajando.pe/wp-content/uploads/2021/06/UPC.png", align="left">
</div>
<div style="float: right; width: 50%;">
<p style="margin: 0; padding-top: 22px; text-align:right;">Creación de Conocimiento a partir de los datos en Python</p>
<p style="margin: 0; text-align:right;">Curso:<b> Administración de Datos</b></p>
<p style="margin: 0; text-align:right;">Profesora: <b>Patricia Reyes Silva</b></p>
</div>
<div style="width:100%;">&nbsp;</div>
<center><h1>TA1</h1></center>

# Contenido

1. [Objetivo del Trabajo](#data1)

2. [Alumnos Participantes del Proyecto](#data2)

3. [Conjunto de Datos](#data3)
    
4. [Conclusiones](#data4)
  


## 1. Objetivo del Trabajo <a name="data1"></a>
    
El Objetivo del trabajo consta en identificar las características que tienen en común los videos que son tendencia en la plataforma “Youtube” a través de un análisis de datos. Esto permitirá responder a diversas incógnitas e identificar la posibilidad de predicción de "Vistas", "Me Gusta" y "No Me Gusta".

## 2. Alumnos <a name="data2"></a>
    
   Los Alumnos que han estado involucrados en el desarrollo de estre trabajo son:
    
    - Joaquin García Guzmán             [u201713735]
    
    - Richard José Maguiña Bernuy       [u202021097]
    
    - Enzo Alexander Huacacolque Toledo [u201620508]
    

## 3. Conjunto de Datos <a name="data3"></a>

El caso analizado en el trabajo proviene del conjunto de datos recolectados por parte de Mitchell J acerca de los videos más populares de la plataforma de Youtube.  Los videos que se han seleccionado para este caso son del país de Alemania, desde el 2017 hasta el 2018. Este conjunto de datos se encuentra publicado en la plataforma “Kaggle” con el nombre del dataset como “Trending YouTube Video Statistics” la cual esta conformado por 20 variables.
    
<table>
<thead><tr><th scope=col>#ID</th><th scope=col>Nombre</th><th scope=col>Tipo</th><th scope=col>Descripción</th></tr></thead>
<tbody>
	<tr><td>1                                                  </td><td>video_id                                                  </td><td>Texto                                                 </td><td>Indica el identificador del video, al cual pertenecen los datos.                           </td></tr>
	<tr><td>2                                                  </td><td>trending_date                                                 </td><td>Fecha                                                 </td><td>Indica la fecha en la cúal el video fue tendencia.</td></tr>
	<tr><td>3                                                  </td><td>title                                                  </td><td>Texto                                                  </td>                             <td>Indica el título del vídeo.                                               </td></tr>
	<tr><td>4                                                  </td><td>channel_title                                                 </td><td>Texto                                                 </td><td>Indica el nombre del canal que publicó el video.       </td></tr>
	<tr><td>5                                                  </td><td>category_id                                                </td><td>Número                                                 </td><td>Indica la categoría al que pertenece el video.                         </td></tr>
	<tr><td>6                                                  </td><td>publish_time                                                 </td><td>Fecha                                                 </td><td>Indica la fecha en la cúal el video fue publicado.                                   </td></tr>
    <tr><td>7                                                  </td><td>tags                                                 </td><td>Texto                                                 </td><td>Indica las etiquetas asociadas al video.                                   </td></tr>
    <tr><td>8                                                  </td><td>views                                                 </td><td>Número                                                 </td><td>Indica la cantidad de vistas obtenidas del video.                                   </td></tr>
    <tr><td>9                                                  </td><td>likes                                                </td><td>Número                                                </td><td>Indica la cantidad de me gustas obtenidos del video.                                   </td></tr>
    <tr><td>10                                                  </td><td>dislikes                                                 </td><td>Número                                                </td><td>Indica la cantidad de no me gustas obtenidos del video.                                   </td></tr>
    <tr><td>11                                                  </td><td>comment_count                                                 </td><td>Número                                                 </td><td>Indica la cantidad de comentarios obtenidos del video.                                   </td></tr>
    <tr><td>12                                                  </td><td>thumbnail_link                                                </td><td>Número                                                 </td><td>Indica el enlace en el que se encuentra la miniatura del video.                                   </td></tr>
    <tr><td>13                                                  </td><td>comments_disabled                                                </td><td>Booleano                                                </td><td>Indica si los comentarios han sido deshabilitados para el video.                                   </td></tr>
    <tr><td>14                                                  </td><td>ratings_disabled                                                </td><td>Booleano                                                </td><td>Indica si los ratings han sido deshabilitados para el video.                                   </td></tr>
    <tr><td>15                                                  </td><td>video_error_or_removed                                                </td><td>Booleano                                                 </td><td>Indica si hubo un error o si el video ha sido removido.                                  </td></tr>
    <tr><td>16                                                  </td><td>description                                                 </td><td>Texto                                                </td><td>Indica una descripción del video.                                  </td></tr>
    <tr><td>17                                                  </td><td>state                                                 </td><td>Texto                                                 </td><td>Indica el estado desde el cúal fue publicado el video.                                   </td></tr>
    <tr><td>18                                                  </td><td>lat                                                 </td><td>Número                                                </td><td>Indica la latitud geográfica del estado.                                   </td></tr>
    <tr><td>19                                                  </td><td>lon                                                </td><td>Número                                                 </td><td>Indica la longitud geográfica del estado.                                  </td></tr>
    <tr><td>20                                                  </td><td>geometry                                                </td><td>Texto                                                </td><td>Indica las coordenadas del estado.                                  </td></tr>
</tbody>
</table>

La finalidad del análisis de este caso es utilizar la información de los videos para conocer más sobre cuáles son los de mayor tendencia y así identificar qué características son las que están presentes mayormente en estos tipos de videos. Y, mediante el uso de estos datos brindados, hemos podido desarrollar un análisis exploratorio de datos para responder las incógnitas dadas.   
	
Adjuntamos nuestro archivo PDF en donde explicamos los pasos utilizados para el análisis de datos, nuestras respuestas ante las preguntas hechas y nuestras conclusiones preliminares del proyecto:
	
    Archivo PDF: https://docs.google.com/document/d/1YxxyHUyxA2617R70M0AJFEoNXZC-hBJYUGAfqXs332c/edit?usp=sharing (Convertir a PDF)
    

## 4. Conclusiones <a name="data4"></a>
    
Como conclusión general, el uso de Python para la administración de los datos es una herramienta muy favorable ya que te da muchas opciones para la gestión de grandes cantidades de datos. Asimismo, su manejo, procesamiento y análisis gráfico nos han podido ayudar en el desarrollo y demostración de nuestras conclusiones a las incógnitas del trabajo.
  
© 2021 The Author(s). by UPC
