Listas_Tablas_y_Algo_m-s
========================
<!DOCTYPE html>
<html>
    
    <head>
        <link type="text/css" rel="stylesheet" href="stylesheet.css" />
        <title>listas y tablas</title>
        <meta charset="utf-8" />
    </head>
    
    <body>    
         <h1>Listas, Tablas y algo más<h1>
                
                
                <!--listas -->
  <h2>1. Listas</h2>
  <p>Las listas pueden ser ordenadas y no ordenadas. Para esto vamos a utilizar las etiquetas:</p>
<table>
   <tr>
       <td><b>&ltol&gt&lt/ol&gt</b></td><td>Para crear listas ordenadas, quiere decir que van numeradas</td></tr>
   <tr>
       <td><b>&ltul&gt&lt/ul&gt</b></td><td>Para crear listas no ordenadas o sea sin numeración, pero con viñetas</td></tr>
   <tr>
       <td><b>&ltli&gt&lt/li&gt</b></td><td>Estas van rodeando cada elemento de la lista</td></tr>
</table>
<p>Podemos  hacer una lista entre otra lista, siempre teniendo en cuenta que la  última lista que empezamos sea la primera que se cierra. Ejemplo:</p>
<table>
    <tr>
        <td class="1">
      &nbsp;&nbsp;&nbsp;&nbsp;<b>&lth2&gt</b>Integrantes de las danzas<b>&lt/h2&gt</b></br>
 &nbsp;&nbsp;&nbsp;&nbsp;<b>&ltul&gt</b></br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltli&gt</b>Niños<b>&lt/li&gt</b></br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltol&gt</b></br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltli&gt</b>Manuel<b>&lt/li&gt</b></br>                                             
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltli&gt</b>Jaiver<b>&lt/li&gt</b></br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltli&gt</b>Sebastian<b>&lt/li&gt</b></br>                                                    
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&lt/ol&gt</b></br>                                                                        
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltli&gt</b>Niñas<b>&lt/li&gt</b></br>                                                         
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&ltol&gt</b></br>                                                                             
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp;&nbsp;&nbsp;
 <b>&ltli&gt</b>Vanesa<b>&lt/li&gt</b></br>                                                 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <b>&ltli&gt</b>Daniela<b>&lt/li&gt</b></br>                                                
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
 <b>&ltli&gt</b>Sarita<b>&lt/li&gt</b></br> 
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<b>&lt/ol&gt</b></br> 
 <b>&lt/ul&gt</b></br>
         </td>
         <td class="2">
<h2>Integrantes de las danzas</h2>
 <ul>
     <li>Niños</li>
         <ol>
             <li>Manuel</li>                                             
             <li>Jaiver</li>
             <li>Sebastian</li>                                                    
         </ol>                                                                        
     <li>Niñas</li>                                                         
         <ol>                                                                             
             <li>Vanesa</li>                                                 
             <li>Daniela</li>                                                
             <li>Sarita</li> 
         </ol> 
</ul>
            </td>
        </tr>
 </table>  


            <!--tablas -->
	<h2>2. Tablas</h2>
	<p>Una tabla es un grupo de información ordenada en filas y columnas. La primera etiqueta que usaremos es:</p>
<p><b>&lttable&gt&lt/table&gt</b> para crear tablas</P>
<p>Una tabla se divide en  encabezado y cuerpo.</p>


              <!--encabezado de tablas -->
	 <h2>2.1. Encabezado de la tabla</h2>
	 <p>El encabezado nos ayuda a darle estilo a nuestra tabla, es donde van los títulos.</p>
<table>
    <tr>
        <td><b>&ltthead&gt&lt/thead&gt</b></td><td> Es el encabezado de tabla (del inglés table head). Contiene los títulos de la tabla.</td></tr>
    <tr>
	<td><b>&ltth&gt&lt/th&gt</b></td><td> Son las celdas en el encabezado de una tabla y en cada una de las celdas puede ir un título</td></tr>
</table>
<b>colspan</b> Es un atributo que se utiliza con la etiqueta <b>&ltth&gt y &lt/th&gt</b> para que la tabla que por defecto ocupa 1 columna, cubra la cantidad de columnas que necesitemos en la tabla. Debemos dar el número de columnas.
Ejemplo:</p>
         <p><b>&ltth colspan="3"&gt&lt/th&gt</b> Ocupara el espacio de tres columnas</p>


       <!--cuerpo de la tabla -->
	<h2>2.2. Cuerpo de la tabla</h2>
<table>
	<tr>
        <td><b>&lttbody&gt&lt/tbody&gt</b></td><td> Cuerpo de tabla (del inglés table body). Contiene los datos tabulares de la tabla.</td></tr>
     <tr>
         <td><b>&lttr&gt&lt/tr&gt</b> </td><td>Para crear una fila de la tabla</td></tr>
     <tr>	
	<td><b>&lttd&gt&lt/td&gt<b></td><td>Es una celda con uno de los datos de la tabla.</td></tr></table>
<p>Para crear columnas en cada fila se incluye una celda por  cada columna.</p>
	</p>
    <p>Un ejemplo de una tabla donde se muestra como se escribe una tabla con dos columnas, en la primera columna: dos imagenes, una con enlace y la otra sin enlace y en la segunda columna dos textos, uno sin enlace y el otro con enlace:</p>
    
    
    
        <!--tabla de demostración --><!-- -->
<table>
    <thead>
        <th>Como se escribe</th><th>Imagenes</th><th>Enlaces</th>
    </thead>
    <tbody>
       <tr class="tablad">
           
           
                   <!--como se escribe html -->
            <td>
         <b>&lttable&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&ltthead&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&ltth&gt Imagenes &lt/th&gt&ltth&gt Enlaces &lt/th&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&lt/thead&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&lttbody&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttr&gt</br>
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttd&gt
</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lta href="http://www.codecademy.com/">&ltimg src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3Rc_QdAQv_BH2ULhm37_FIbKxxTJrqy_jXuS34zatsBFlE3kG_MVywdcW" /&gt&lt/a&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/td&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttd&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&ltp&gt El enlace esta sobre la imagen &lt/p&gt</br>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/td&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/tr&gt</b>
        </td> 
        <td>
	    <a href="http://www.codecademy.com/"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT3Rc_QdAQv_BH2ULhm37_FIbKxxTJrqy_jXuS34zatsBFlE3kG_MVywdcW" /></a>
        </td>
	<td><p>El enlace está sobre la imagen</p>
	</td>
    </tr>  
    <tr>
	<td><b>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttr&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttd&gt
</br>		
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&ltimg src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStcyeKaDP39kjrDwZoA6rDZWRCVfB8kySA71xQ_xONKssTgqhBwUHIdm3E" /&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/td&gt
</br>		
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lttd&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lta href="https://www.google.com.co/search?q=paisajes+naturales&oq=paisajes&qs=chrome.2.69i57j0l5.5450j0j7&sourceid=chrome&es_
sm=88&ie=UTF-8"&ltp&gtPaisajes&lt/p&gt&lt/a&gt</br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/td&gt</br>
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt/tr&gt</br>
 &lt/table&gt</b></br>
			<td><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcStcyeKaDP39kjrDwZoA6rDZWRCVfB8kySA71xQ_xONKssTgqhBwUHIdm3E" />
        </td>
        <td><a href="https://www.google.com.co/search?q=paisajes+naturales&oq=paisajes&aqs=chrome.2.69i57j0l5.5450j0j7&sourceid=chrome&es_sm=88&ie=UTF-8"><p>Paisajes</p></a>
	</td>
    </tr>
</table>


         <!--border -->
	<h2>3. Propiedad border</h2>
	Se usa para demarcar los bordes de la tabla. Se pone como valor del atributo style seguido del signo igual(<b>=</b>) a uno o varios valores entre las comillas (<b>" "</b>) separados por espacios</p>

<table>
    <tr>
     <td></td><td></td><td></td><td></td><td style="background-color: #B9F5DA;">Valor del atributo Style</td><td></td><td></td><td></td><td></td>
    </tr>
    <tr>    
     <td></td><td></td><td></td><td></td><td>&darr;</td><td></td><td></td><td></td><td></td>  
    </tr> 
    <tr>    
        <td>&lt</td>
        <td style="color: #FF0000;">table</td>
        <td style="color: #FF0066; ">style</td>
        <td>=</td>
        <td style="color: #FB052A; background-color: #B9F5DA;"> "border:</td>
        <td style="color: #0B0580; background-color: #B9F5DA;">1px solid  blue ;"&gt</td>
        <td></td><td></td>
        <td></td>
        <td></b></td>
     </tr>
     <tr>
        <td></td><td style="color: #FF0000;">&uarr;</td>
         <td style="color: #FF0066;">&uarr;</td><td></td><td style="color: #FB052A;">&uarr;</td><td style="color: #0B0580;">&uarr;</td><td></td><td></td><td></td>
     </tr>
      <tr>
          <td></td><td style="color: #FF0000;">etiqueta</td><td style="color: #FF0066;">atributo</td><td></td><td style="color: #FB052A;">propiedad css</td><td style="color: #0B0580;">valor de la propiedad border</td><td></td><td></td><td></td>
     </tr>
</table>    
<p>Los bordes se pueden definir uno por uno o los cuatro a la vez; cuando definimos uno a uno se empieza por el borde superior, luego el borde derecho, despues el borde inferior y por ultimo el borde izquierdo separados por un espacio entre si. </p>
<table>
    <tr>
        <td></td><td></td><td></td><td></td><td></td><td></td><td style="color: #FF0000;">derecha</td><td></td><td style="color: #FF0066;">izquierda</td></tr>  
    <tr> 
        <td></td><td></td><td></td><td></td><td></td><td></td><td>&darr;</td><td></td><td>&darr;</td></tr>  
     <tr> 
         <b><td>&lt</td><td> table</td><td> style</td><td>=</td><td> "border:</td><td style"color: #006600;"> 3px</td><td style="color: #FF0000;" > 4px</td><td style="color: #CC0000;"> 3px</td><td style="color: #FF0066;"> 5px;</td><td>"&gt</td></b>
    </tr>
     <tr>
        <td></td><td></td><td></td><td></td><td></td>
         <td style"color: #006600;">&uarr;</td><td></td><td>&uarr;</td><td></td></tr>  
    <tr> 
        <td></td><td></td><td></td><td></td><td></td><td>superior</td><td></td><td style="color: #CC0000;">inferior</td><td></td></tr>
</table>
<p>Algunos de los valores de border son:</p>
<table>
    <tr>
	<td><b>#px</b></td><td> Grosor de la línea (lo específica en número de pixeles)</td></tr>
    <tr> 	
	<td><b>solid</b></td><td> Línea continua</td></tr>
    <tr>
	<td><b>dashed</b></td><td> Línea discontinua</td></tr>
    <tr>
	<td><b>separate</b></td><td> Independiente</td></tr>
    <tr>
	<td><b>collapsablee</b></td><td> Une los bordes de las celdas adyacentes</td></tr>
   <tr> 
	<td><b>color</b></td><td> Color </td></tr>
   <tr>
	<tr>
	<td><b>padding</b></td><td>Indica el espacio entre el borde y el contenido de la tabla</td></tr>
      	</table>
<table>
    <tr>
	<td><b>&lttd style="padding:5px;border: 1px solid black;<b>"&gt&lt/td&gt</b></td><td>Relleno para todos los lados.</td></tr></table>
<p>El atributo border tambien se puede especiicar más para hablar de un sólo borde. Ejemplo.</p>
<p><b>border-righ-color</b> que hablamos del color del borde derecho.</p>
    
    
              <!--etiquetas autocerradas -->
<h2>6. Etiquetas autocerradas</h2>
<p>Las etiquetas de autocerrado son las etiquetas que no admiten contenido. Algunas de ellas son:</p>
<table>
    <tr>
	<td class="1"><b>&ltbr /&gt</b></td><td class="2">Se utiliza para crear un salto de línea.  Pasa al otro renglon</td></tr>
    <tr>
	<td class="1"><b>&ltmeta /&gt</b></td><td class="2">Indica el tipo de codificacion que estamos utilizando</td></tr>
    <tr>
	<td class="1"><b>&ltimg /&gt</b></td><td class="2">Se utiliza para insertar una imagen</tr>
    <tr>
	<td class="1"><b>&ltlink /&gt</b></td><td class="2">Se utiliza para enlazar un archivo HTML con otros archivos </td></tr>
    <tr>
	<td class="1"><b>&lthr /&gt</td class="2"></b><td>Representa una línea horizontal para separar diferentes secciones de un documento</td></tr>
    <tr>
	<td class="2"><b>&ltinput /&gt</b></td><td>Se utiliza para el ingreso de datos del usuario./td></tr>
    </td><tr>
</table>
        
        
            <!--flechas -->
<p>&larr;	Flecha hacía la izquierda</br>
&uarr;	Flecha hacía arriba</br>
&rarr;	Flecha hacía la derecha</br>
&darr;	Flecha hacía abajo</br>
&harr;	Flecha a izquierda y derecha</br>
&crarr;	Flecha de retorno de carro</br>
&lArr;	Flecha doble hacía la izquierda</br>
&uArr;	Flecha doble hacía arriba</br>
&rArr;	Flecha doble hacía la derecha</br>
&dArr;	Felcha doble hacía abajo</br>
&hArr;	Flecha doble a izquierda y derecha</p>
        
        
      
    <!--bibliografía -->
<h2>Bibliografías</h2>
<p><strong>HTML color codes</strong></br>
    http://html-color-codes.info/codigos-de-colores-hexadecimales/</br>
    Para buscar colores css</p>
<P><strong>LIBROSWEB</strong></br>
    http://librosweb.es/referencia/css/</p>
<P><strong>IRONSPIDER</strong></br>
http://www.ironspider.ca/webdesign102/tables4layout2.htm</br>
Tiene ejemplos de paginas y explicaciones</p>
<p><strong>Haz Una Web.Com</strong></br>
http://html.hazunaweb.com/106.php</p>
<p><strong>Aula clic</strong></br>
http://www.aulaclic.es/access-2010/index.htm</p> 
<p><strong>publiceuta</strong></br>
http://www.publiceuta.com/manuales/etiqueta.htm</p>
<p><strong>Virtualnauta</strong></br>
http://www.virtualnauta.com/html-etiqueta-br</p>
<p><strong>Vagabundia</strong></br>
    http://vagabundia.blogspot.com/2008/02/las-propiedades-css-margin-padding-y.htm</p>
<p><strong>DESARROLLADORES WEB</strong></br>
http://www.desarrolloweb.com/articulos/atributo-position-css.html</p>
<p><strong>W3SCHOOLS.COM</strong></br>
http://www.w3schools.com/cssref/pr_class_float.asp</p>


    </body>
</html>
