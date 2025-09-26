# Guía Instalación Wordpress en Ubuntu Server 24.04
![img.png](./img.png)
## Instalación
### Instalacion del servidor web

Instalamos el servidor web con el siguiente comando

<img width="1695" height="504" alt="image" src="https://github.com/user-attachments/assets/c10e2186-7e55-470b-9f61-6edcacbfcf94" />


### Base de datos
Aunque esta maquina ya trae una base de datos voy a hacer lo que me dice el tutorial por asegurar compatibilidad y pereza para las cosas, tambien aprovecho y meto algunas

<img width="1782" height="204" alt="image" src="https://github.com/user-attachments/assets/21b4271b-1889-4fa0-9641-23807ff0ff5d" />


<img width="720" height="109" alt="image" src="https://github.com/user-attachments/assets/6383e698-3e9e-4553-86c4-1bb3ac58ed83" />

### Descarga e instalacion de Wordpress
Descargamos el comprimido que contiene el aplicativo de Wordpress desde su pagina oficial

<img width="711" height="422" alt="image" src="https://github.com/user-attachments/assets/f084f4aa-eb8b-4a56-b44b-62379c3a9315" />

Hacemos que la carpeta que contiene wordpress sea la carpeta que el servidor utilizar, y le damos los permisos correspondientes para asegurar que se puedan llevar a cabo las configuraciones, además es necesario para poder realizar la instalacion y que no haya problemas en el proceso, además si no lo hacemos nos pedira credenciales para un servidor FTP para descargar plugins, por el hecho de que no puede escribir directamente en lo que tengo

<img width="1782" height="204" alt="image" src="https://github.com/user-attachments/assets/072fdbe8-f48a-447e-a21c-438b80cb9507" />



## Configuracion
### Configuraciones de la base de datos

<img width="1782" height="204" alt="image" src="https://github.com/user-attachments/assets/03222cc0-de94-4898-938c-424e1b867695" />


Entramos a la base de datos y aplicamos algunas configuraciones

<img width="1777" height="574" alt="image" src="https://github.com/user-attachments/assets/b701d57d-099e-45f0-a16c-4ab2e67bfa5b" />


### Configuracion del servidor web
Activamos lo que necesitamos a nivel del servidor apache,segun lo que he buscado seria algo así

<img width="1777" height="533" alt="image" src="https://github.com/user-attachments/assets/ae7790ad-e6c3-4541-ad39-7ea683b12452" />


### Configuracion de Wordpress

Nos pide configurar el idioma

<img width="1859" height="755" alt="image" src="https://github.com/user-attachments/assets/f748b422-fdad-4625-b79d-365f5f880bf2" />


Introducimos las credenciales de nuestra base de datos en la pagina que wordpress nos proporciona

<img width="1859" height="755" alt="image" src="https://github.com/user-attachments/assets/8fa8d442-b358-4c71-8880-237558195160" />

Aqui nos apareceria un boton de realizar instalacion. Yo simplemente le di, **Ojo** si no configuras bien los permisos de la manera en la que mostre antes es necesario copiar el contendio del archivo **wp-config.php** y escribirlo manualmente.

Tal y como muestro a continuacion

<img width="843" height="824" alt="image" src="https://github.com/user-attachments/assets/a4474ad4-c363-4f61-8ab1-7f2037dab343" />

#### Informacion del sitio

<img width="1889" height="969" alt="image" src="https://github.com/user-attachments/assets/797bde99-63d4-4204-a3f0-798b84dc77c5" />

### Personalizacion y toques finales

<img width="1903" height="919" alt="image" src="https://github.com/user-attachments/assets/c8f6aad6-7443-48a8-ad8d-362da593c7c6" />

#### Wordpress con el tema activado

Aqui muestro la pagina de Wordpress con el tema personalizado activado, uso el tema Blogier

<img width="1903" height="919" alt="image" src="https://github.com/user-attachments/assets/6ebba131-6565-4636-abef-cf75e8d5f1e1" />

Aqui la imagen de la informacion en la tienda de temas
<img width="1889" height="969" alt="image" src="https://github.com/user-attachments/assets/9e009532-3437-4ea2-a153-845eba83907e" />

#### Plugins
Aqui voy a poner una lista de plugins 

##### Complianz
Es un plugin para poner Banners de Cookies que soportan el ser configurados segun diversas politicas de privacidad, permitiendo poner una politica de cookies personalizada

<img width="840" height="816" alt="image" src="https://github.com/user-attachments/assets/587f39f1-af5c-43cc-8363-770edb979a9d" />

##### Autoptimize
Es para optimizar la pagina de Wordpress, segun su pagina en el sitio de wordpress

<img width="840" height="816" alt="image" src="https://github.com/user-attachments/assets/4690a717-eae3-4b49-9a34-5e232bc1c4af" />

##### Polylang
Te permite crear sitios multilingües de una manera facil, dandote opciones para tener sitios con varios idiomas, tiene una version pro que ofrece más caracteristicas [Pagina de Wordpress del plugin](https://wordpress.org/plugins/polylang/)

<img width="840" height="816" alt="image" src="https://github.com/user-attachments/assets/bede4629-8f2a-40f1-b8ed-290152d86479" />

Una vez esta instalado te proporciona esta pagina para empezar a configurar
<img width="840" height="816" alt="image" src="https://github.com/user-attachments/assets/c70b95e9-5e48-4a3b-935d-69c3e8d2b526" />


