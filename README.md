# Presentación y notebooks del webinar sobre desarrollo y consumo de API basadas en REST.

Notebooks de [Jupyter](https://jupyter.org) que incluyen los apuntes del webinar sobre desarrollo y consumo de API basadas en REST de Cloudevel®.

## Nuestra máquina virtual.

Para facilitar la instalación y configuración de Jupyter se recomienda descargar nuestra VM de [Virtualbox](https://virtualbox.org) la cual puede ser descargada desde https://cloudevel.com/downloads/base/view. Una vez que se ejecute la VM podrá acceder a un servidor de Jupyter totalmente funcional ingresando desde el navegador de su equipo en la dirección ```http://localhost:8999``` con la contraseña ```Jupyter```.

## Clonación del repositorio.

Para clonar el repositorio en su sitema de archivos local, ejecute desde una terminal:

``` bash
git clone https://github.com/Cloudevel/api_rest_webinar.git
```

## Contenido del repositorio.

Este repositorio contiene las notebooks de Jupyter, los datos y el archivo HTML correspondientes a:

* La presentación del webinar escrita como notebook de Jupyter ([RESTful.ipynb](RESTful.ipynb)) así como en HTML ([RESTful.slides.html](http://htmlpreview.github.com/?https://github.com/josechval/api_rest_webinar/blob/master/RESTful.slides.html)).
* Un servidor simple de API REST basado en Flask [servidor_api_rest.pynb](servidor_api_rest.ipynb).
* Un cliente que consume la API REST del servidor basado en la biblioteca requests [cliente_api_rest.ipynb](cliente_api_rest.ipynb).
* Un cliente que consume información de la API de Twitter utilizando la biblioteca requests-oauthlib [acceso_api_twitter.ipynb](acceso_api_twitter.ipynb).

## Video del webinar.

El video de la presentación está disponible en https://www.youtube.com/watch?v=qhqCJSmdKvY.
