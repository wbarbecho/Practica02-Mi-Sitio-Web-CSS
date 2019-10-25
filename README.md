Practica02-Mi-Sitio-Web-CSS
===========================

Comenzamos creando el index.html con la cual vamos a utilizar el modelo de 2
columnas en CSS, con esto se puede realizar las pruebas adecuadas para así
posteriormente acoplar a las demás páginas.

Al momento de generar los archivos html usaremos selectores e ID para de esta
manera identificar el o los elementos que deseamos agregar cierto estilo o
modificación por medio de CSS. Dentro de HTML también usaremos la etiqueta
“\<div\>” para que con esto nos permita tratar a los elementos como objetos
diferentes dentro del body.

**\<div class="logo"\>**

Con eso agregamos los los estilos de CSS (aunque todavía no presente código)
para de esta manera ir modificando el estilo de cada uno de estos.

**\<link type="text/css" rel="stylesheet" href="css/estilos.css"\>**

**\<link type="text/css" rel="stylesheet" href="css/dos_columnas.css"\>**

Dentro de estilos.css seleccionamos el color de fondo y también la dimensión de
HTML, este caso usaremos para ancho “width: 100vw”, altura “heigh: 100vh”. Estas
unidades de vw y vh son “viewport” y estas son medidas relativas con lo cual se
podría visualizar en diferentes resoluciones tales como de un dispositivo
celular hasta un monitor de alta resolución.

![](media/9c1bed2241c6af3484598af5948a070d.png)

![](media/ba48a69487733644196d989a5a0cd6cb.png)

Como se puede apreciar en las imágenes en el primero esta maximizado mientas que
el segundo caso se minimiza a su mínima dimensión.

De igual manera como se solicita la las etiquetas h1,h2,h3 presentan un diseño
diferente*:*

**h1 {**

**font-size: 1.5em;**

**text-align: center;**

**text-decoration: underline overline;**

**}**

**h2 {**

**font-size: 1.5em;**

**color: rgb(91, 183, 219);**

**text-align: center;**

**}**

**h3 {**

**font-size: 1em;**

**color: black;**

**}**

![](media/9c1bed2241c6af3484598af5948a070d.png)

La navegación de igual manera que se pide presenta bordes redondeados en este
caso con un valor de 25px.

![](media/1d63cf336365b0ea68254a2d076c0495.png)

La ventana de formulario presenta un cambo para el nombre, email y mensaje cada
uno de estos presenta una etiqueta para que su dimensión del área de texto sea
la misma en el ancho, también se le asigna el espacio de las “cajas” de nombre
email y mensaje.

HTML

**\<div id="formu"\>**

**            \<section\>**

**                \<div\>**

**                    \<label for="name"\>Nombre:\</label\>**

**                    \<input type="text" id="name" /\>**

**                \</div\>**

**                \<div\>**

**                    \<label for="mail"\>E-mail:\</label\>**

**                    \<input type="email" id="mail" /\>**

**                \</div\>**

**                \<div\>**

**                    \<label for="msg"\>Mensaje:\</label\>**

**                    \<textarea id="msg"\>\</textarea\>**

**                \</div\>**

**                \<div class="button"\>**

**                    \<button type="submit"\>Enviar mensaje\</button\>**

**                \</div\>**

**            \</section\>**

**        \</div\>**

CSS

**label {**

**  display: inline-block;**

**  width: 90px;**

**  text-align: right;**

**}**

**input,**

**textarea {**

**  width: 300px;**

**  box-sizing: border-box;**

**}**

**textarea {**

**  vertical-align: top;**

**  height: 5em;**

**  resize: vertical;**

**}**

**.button {**

**  padding-left: 175px;**

**}**

**La evidencia del correcto diseño de las páginas HTML usando CSS. Para lo cual,
se puede generar fotografías instantáneas (pantallazos).**

![](media/c4852f9b5b0b35b0cf8c7ff2eb39ec1c.png)

![](media/757f47d947ed2db238876f7631e82ca8.png)

![](media/1eeb6cc50607c91851b0f87980f4dfb8.png)

![](media/6841c05311ee17e0b27362766b08a84c.png)

![](media/2f9e7f534e3f49e088bfeb3203f60db9.png)

Estilo de 3 columnas de una página.

**La evidencia de la validación de cada página HTML.**

![](media/148cdc6f87d0bebce6d1df1f8135d81b.png)

![](media/3119249eed57fd40478ec5662dc945b8.png)

![](media/b76bd6567e7856c8549718b1f251e2eb.png)

![](media/54329010a5cab2d1aadb001a4aa05425.png)

![](media/e1eb5fd23baa71812d21d5b39f3a5c69.png)

![](media/7b58ed2ee36a93921d61a0cc1fce9a1a.png)

**La evidencia de la validación de las hojas de estilos CSS.**

![](media/8bf88f73b622e799a434801522b144c1.png)

![](media/0f4bd85373b85af54de587ac0d735583.png)

![](media/a47e7d8d42d9b21a1d90edc7ff04fd2d.png)

**En el informe se debe incluir la información de GitHub (usuario y URL del
repositorio de la práctica)**

Usuario: wbarbecho

Link: <https://github.com/wbarbecho/Practica02-Mi-Sitio-Web-CSS>

**Tutorial**

Usuario: wbarbecho

Link: <https://github.com/wbarbecho/Tutorial-02---1TriAndSuccedSports>
