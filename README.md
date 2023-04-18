# theme-child-bus
**Idioma: Español.**

***Es un tema hijo de wordpress con un formulario en front-end para crear post de buses con imagenes***

**Language: English.**

***It is a wordpress child theme with a front-end form to create bus post with images***


### Los 9 shortcode para crear el formulario front-end para publicar los bus

1. **Inicio del formulario "Es Obligatorio ser el primero en colocar"**
```
    [bus_destacada_img]
```


2. **Campo para ingresar la imagen destacada de la publicacion tiene para editar el corte de imagen**

**(Opcional) parametro _label=valor_ por defecto "Click aquí para subir la foto del autobús y editarla"**
```
    [bus_destacada_img]
```


3. **Campo para ingresar varias imagenes aparte de la imagen destacada que se mostrara en el eslider**

**class por defecto "bus-file-slider"**
```
    [bus_slider_img]
```


4. **Campo para ingresar la placa que sera el titulo de la publicacion bus**

**(Opcional) parametro _placeholder=valor_ por defecto "Escribir el identificador del Bus", class por defecto "bus-input-title"**
```
    [bus_input_placa] 
```



5. **Campo para ingresar el contenido de la publicacion que es la descripcion**
**(Opcional) parametro _placeholder=valor_ por defecto ""**
```
    [bus_textarea_descrip] 
```



6. **Campo selector de las provincia de la placa del bus**

**class por defecto "bus-select-provincia"**
```
    [bus_select_provincia] 
```



7. **Campo selector o texto para ingresar el autor de la fotografia a publicar**

**class por defecto "bus-select-fotografo"**
```
    [bus_select_fotografo] 
```


8. **Campo selector para ubicar la publicacion en el menu donde se mostrara por provincia y por año del bus**

**class por defecto "bus-select-menu"**
```
    [bus_select_menu] 
```


9. **Boton para guardar los datos de la publicacion para que sea revisado por el administrador del sitio**
**(Opcional) parametros _text=valor_ por defecto "Publicar", _class=valor_ por defecto "btn-publicar"**
```
    [bus_publicar_btn] 
```



**Obligatoriamente tiene que estar al final del formulario ya que cierra el form**

**Ejemplo del formulario para publicar desde el front end**

![Imagen de ejemplo del formulario](https://github.com/jafr0691/wp-theme-child-form-front-end/blob/master/imgReadme/publicarBus.jpg)

**Fin del formulario front-end para crear los post**




### Los 4 shortcode para mostar los datos de la publicacion del bus en la ficha tecnica

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
**Ejemplo del loop post publicado desde el front end**

![Imagen de ejemplo del loop post desde el front end](https://github.com/jafr0691/wp-theme-child-form-front-end/blob/master/imgReadme/postBus.jpg)


**Ejemplo del post publicado desde el front end**

![Imagen de ejemplo del post desde el front end](https://github.com/jafr0691/wp-theme-child-form-front-end/blob/master/imgReadme/postBus.jpg)


**Para mostrar la imagen destacada se usa con el editor del plugins elementor > elementos > imagen > se agrega que tome el dato de "featured image"**

**Para mostrar la placa que es el titulo del bus publicado con el editor del plugins elementor > elementor > editor de texto > se agrega que tome el dato de Post title**

**Para mostrar el autor de la fotografia del bus publicado con el editor del plugins elementor > elementor > editor de texto > se agrega que tome el dato de Post terms + taxonomia fotografo**

