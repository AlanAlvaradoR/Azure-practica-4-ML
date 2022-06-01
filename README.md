# Azure-práctica-4-ML
Creación de Machine Learning en Azure

![Logo de ML](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/ML.jpg)

## Requisitos

- Cuenta de [Azure](https://portal.azure.com/) con suscripción activa
- Computadora con Windows, Linux o MacOs
- Si se desea programar desde un editor de código fuente como Visual Studio Code, se tiene que [descargar](https://code.visualstudio.com/) e instalar

---------------------------------------------------------

## Pasos

- Se inicia sesión en la página de [Azure](https://portal.azure.com/)

![Inicio Azure](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/inicio%20Azure.PNG)

- Se busca "Machine Learning" en el buscador superior y se da enter

![P4-2](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-2.PNG)

- En la pestaña que se abre le damos en "crear"

![P4-3](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-3.PNG)

- En la nueva pestaña nos dirigimos al apartado "grupo de recursos" y presionamos en "crear nuevo", se desplegará un sub-menú donde debemos colocar el nombre del nuevo grupo de recursos y presionamos "aceptar" en el sub-menú

![P4-4](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-4.PNG)

- Bajamos un poco hasta el apartado de "Detalles del área de trabajo" donde colocaremos el nombre de nuestra área de trabajo en la parte donde dice "Nombre del área de trabajo" y presionamos le botón de revisión y creación

![P4-5](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-5.PNG)

- Revisamos que todo este en orden y esperamos un momento a que se habilite el botón de crear y después lo presionamos

![P4-6](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-6.PNG)

- Nos mostrará un aviso de que se esta creando el recurso, por lo que esperamos a que termine

![P4-7](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-7.PNG)

- Nos mostrará un anuncio diciendo que ha terminado

![P4-8](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-8.PNG)

- Ingresamos a [Azure Machine Learning](https://ml.azure.com/) e iniciamos sesión

![P4-9](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-9.PNG)

- Seleccionamos el espacio de trabajo que acabamos de crear y presionamos en "ir al espacio de trabajo"

![P4-10](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-10.PNG)

- En el menú de la izquierda seleccionamos "proceso" (puede que tengas que bajar un poco para ver la opción)

![P4-11](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-11.PNG)

- Se abrirá una nueva pestaña, en el apartado de instancias seleccionamos "+ Nueva"

![P4-12](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-12.PNG)

- Se abrirá una pestaña como la siguiente

![P4-13](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-13.PNG)

- Se coloca el nombre del recurso de machine learning y abajo se selecciona el tamaño standard DS11 v2 para el recurso y presionamos el boton "crear"

![P4-14](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-14.PNG)

- Aparecerá una ventana como la siguiente, mientras se crea el recurso el estado aparecerá como "creando"

![P4-15](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-15.PNG)

- Abrimos el menú lateral de la izquierda y seleccionamos "notebook"

![P4-16](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-16.PNG)

- En la parte derecha aparecerá una pestaña como la siguiente

![P4-17](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-17.PNG)

- Presionamos en el botón "+" y después en "crear archivo nuevo"

![P4-18](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-18.PNG)

- En el submenú que aparece, colocamos el nombre del archivo y presionamos el botón "crear"

![P4-19](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-19.PNG)

- Se abrirá una pestaña como la siguiente

![P4-20](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-20.PNG)

- Escribiremos el siguiente código en la notebook para programar un "Hola mundo" en python

![P4-21](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-21.PNG)

- Se presiona el botón de "run" en el lado izquierdo para ejecutar el código y en la parte de abajo inmediatamente veremos el resultado

![P4-22](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-22.PNG)

- Si se desea editar el código en [Visual Studio Code](https://code.visualstudio.com/) en la parte superior se presiona el botón que dice "editar en Visual Studio Code"

![P4-23](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-23.PNG)

- Mientras se abre el Visual Studio Code, se presentarán anuncios y permisos como los siguientes, aceptamos todo

![P4-24](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-24.PNG)

![P4-25](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-25.PNG)

![P4-26](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-26.PNG)

- También puede pedirnos iniciar sesión, en ese caso iniciamos sesión con el correo que tenemos la cuenta de Azure

- Finalmente, Visual Studio Code nos mostrará una ventan con el código que habiamos escrito previamente y, desde ese espacio podemos modificarlo y se ejecutará en nuestro recurso en la nube

![P4-27](https://github.com/AlanAlvaradoR/Azure-practica-4-ML/blob/main/imagenes/P4-27.PNG)
