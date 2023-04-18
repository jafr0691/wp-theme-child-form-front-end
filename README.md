# theme-child-bus
**Idioma: Español.**

***Es un tema hijo de wordpress con un formulario en front-end para crear post de buses con imagenes***

**Language: English.**

***It is a wordpress child theme with a front-end form to create bus post with images***


**Los 8 shortcode para crea el formulario frontend**
+ Formulario para publicar los bus
+ Inicio del formulario "Es Obligatorio ser el primero en colocar"
    **[bus_destacada_img]**

1. **Campo para ingresar la imagen destacada de la publicacion tiene para editar el corte de imagen**

    **[bus_destacada_img]**

**parametro label=valor por defecto "Click aquí para subir la foto del autobús y editarla"**

2. **Campo para ingresar varias imagenes aparte de la imagen destacada que se mostrara en el eslider**

    **[bus_slider_img]**

**class por defecto "bus-file-slider"**

3. **Campo para ingresar la placa que sera el titulo de la publicacion bus**
```
    [bus_input_placa] 
```
**parametro placeholder=valor por defecto "Escribir el identificador del Bus", class por defecto bus-input-title**

4. **Campo para ingresar el contenido de la publicacion que es la descripcion**
```
    [bus_textarea_descrip] 
```
**parametro placeholder=valor por defecto ""**

5. **Campo selector de las provincia de la placa del bus**
```
    [bus_select_provincia] 
```
**class por defecto "bus-select-provincia"**

6. **Campo selector o texto para ingresar el autor de la fotografia a publicar**
```
    [bus_select_fotografo] 
```
**class por defecto "bus-select-fotografo"**

7. **Campo selector para ubicar la publicacion en el menu donde se mostrara por provincia y por año del bus**
```
    [bus_select_menu] 
```
**class por defecto bus-select-menu**

8. **Boton para guardar los datos de la publicacion para que sea revisado por el administrador del sitio**
```
    [bus_publicar_btn] 
```
**parametros text=valor por defecto "Publicar", class=valor por defecto "btn-publicar"**

**Obligatoriamente tiene que estar al final del formulario ya que cierra el form**


**Fin del formulario front-end para crear los post**





# Los 4 shortcode para mostar los datos de la publicacion del bus en la ficha tecnica

1. **Muestra los datos:**
+ fecha de la publicacion
+ Cantidad de vistas
+ Cantidad de comentario
```
    [publicado]
```
2. **Muesta el texto o contenido de la descrpcion publicada**
```
    [bus_descrip] 
```
3. **Muestra el logo o nombre de la empresa de la carroceria del bus publicado**
```
    [empresa_titulo]
```
4. **Muestra las imagenes del slider debajo de la imagen destacada**
```
    [bus_carrusel]
```
**Para mostrar la imagen destacada se usa con el editor del plugins elementor > elementos > imagen > se agrega que tome el dato de "featured image"**

**Para mostrar la placa que es el titulo del bus publicado con el editor del plugins elementor > elementor > editor de texto > se agrega que tome el dato de Post title**

**Para mostrar el autor de la fotografia del bus publicado con el editor del plugins elementor > elementor > editor de texto > se agrega que tome el dato de Post terms + taxonomia fotografo**

