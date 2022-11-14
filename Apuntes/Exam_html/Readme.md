# HTML  

## ***Teoría del examen:***  
### *HTML y evoluxión:*
HTML es un lenguaje creado para crear la mayoría de las páginas web. Es un estandar reconocido por todos los navegadores web, por esa razón todos ellos visualizan una página HTML de forma muy similar. El origen de HTML fue un sistema de hipertexto para compartir documentos electrónicos(1990)  

La primera propuesta oficial para convertir HTML en un estándar fue en 1993, pero no lo consiguió hasta más adelante. HTML 2.0 fue la primera versión oficial publicada como estándar por el IETF. Poco a poco ha ido evolucionando y destacamos: Html 3.2 (incorpora applets de Java), Html 4.0 (Hojas de estilo CSS), Html 4.01 (Versión actualizada del anterior) y Html 5 (versión más avanzada y la considerada actualmente estándar). Lo más destacable de esta nueva versión es que todo lo relativo a la presentación del documento se pasa del HTML a las hojas de estilo CSS.  

### *HTML y XHTML:*  
El lenguaje XHTML es muy similar al lenguaje HTML, de hecho es una adaptación del HTML al XML. Pasar de HTML 4.01 a XHTML no requiere casi ningún cambio (XHTML añade muy pocas cosas en su estábdar respecto a esa versión de HTML).  

HTML es un lenguaje muy permisivo, lo cual da lugar a una sintaxis muchas veces desordenada, con un código desordenado y difícil de mantener. XHTML soluciona estos problemas, añadiendo ciertas normas en la forma de escribir las etiquetas y atributos. Algunas de las normas que tiene que cumplir el documentos para que sea un XHTML bien formado son: Elemeto raíz html, etiquetas y atributos en minúscula, Valor de atributos entre comillas, Cerrar todas las etiquetas... Por último, hay que tener en cuenta que los navegadores no procesan igual XHTML y HTML exactamente igual.  

### ***Estructura y etiquetas:***  

### *Prólogo:*  

Los documentos HTML deben tener título y cabecera. La cabecera está delimitada por las etiquetas de head, y contiene la información sobre el título de la página, autor, palabras clave... Dentro de esta se define el título, información que sale en la etiqueta o título de la pestaña del navegador. En cambio, el cuerpo contiene toda la información a mostrar en pantalla, limitadas entre las etiquetas body.  

Para las versiones HTML 4.0, hay tres prólogos distintos que definen 3 tipos distintos de HTML, con etiquetas del estilo: ```<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">```  

En cambio, para el HTML 5 basta con declarar el documento como HTML de esta forma: ```<!DOCTYPE html>```  

### *Clasificación de atributos:*  
- Atributos globales:
    - name = "texto" (Asignan nombre)
    - title = "texto"  (Asignan un título para mejorar la accesibilidad)
    - id = "texto" (Identifican para aplicar CSS y JS)
    - style = "texto" (Estilo directamente)  
    - class = "texto" (Aplican el estilo "texto" definido la CSS)

- Atributos internacionalización: 
    - dir (Indican la dirección del texto)
    - lang (idioma mediante un código predefinido)  

### *Elementos HTML:*
En un documentos HTML podemos ver:  
- Elementos en línea: Ocupan el espacio necesario para mostrar sus contenidos, puede ser texto u otros elementos en línea  
- Elementos de bloque: Los elementos de bloque empiezan en una nueva línea y ocupan todo el espacio disponible. Su contenido puede ser texto, elementos en línea u otros elementos de bloque.  

## *Elementos de la cabecera:*  
- Elementos contenedores: Tenemos los elementos: title, script (no se interpreta) y style (aplicado al documento usando CSS)  
- Elementos no contenedores: Tenemos: base(URI del documento), link, meta (metadatos como codificación, descripción, autores...)  

## *Encabezados y párrafos:*  
Para agrupar en párrafos un contenido lo encerramos en etiquetas p.  

Y para los encabezados, usamos las etiquetas h1, h2, h3... h6. De mayor a menor en cuanto a tamaño del mismo.  

## *Saltos de línea:*  
Los navegadores, suelen ignorar los saltos de línea, al igual que un cúmulo de espacios consecutivos. Por esa razón, un salto de linea se incluye con una etiqueta br.  

## *Comentarios:*  
En HTML, los comentarios se incluyen con ```<!--comentario-->```.  

## *Semántica a nivel de texto:*  
Tenemos algunos elementos como: 
- < a >: Definen hipervínculos. Después de este ponemos href = "página del vínculo". 
- < strong >: Texto en negrita
- < em >: Indican énfasis en el texto. normalmente parecido a cursiva
- < small >: Para comentarios accesorios que aparecen en letra pequeña  

## *Elementos de listas:*  
Tenemos tres tipos de listas, desordenadas, ordenadas y de definición:  
- ul: Lista desordenada
- ol: Lista ordenada
- dl: Lista de definición
- li: Elementos de lista ordenada o desordenada
- dt: Términos de una lista de definición 
- dd: Definiciones de una lista de definición  

## *Elementos de tablas:*  
Las tablas son una forma habitual de presentar información de manera compacta y fácil. En general, en la tabla se muestran una serie de elementos o datos en filas y columnas. Los elementos de una tabala son:  
- table: Delimita el contenido de la tabla
- tr: Delimita las lineas de la tabla
- td: Delimita el contenido de cada celda de la tabla
- colgroup: Agrupa columnas
- tbody: Agrupa líneas de la tabla
- thead: Define la línea cabecera de la tabla
- th: Delimita cada una de las celdas de la cabecera
- tfoot: Define la fila pie de la tabla
- caption: Añade una leyenda a la tabla  

## *Elementos de formulario:*
