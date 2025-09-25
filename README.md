# Guía Instalación Wordpress en Ubuntu Server 24.04
![img.png](./img.png)
## Instalación
### Instalacion del servidor web

<img width="598" height="34" alt="image" src="https://github.com/user-attachments/assets/46fa6ca7-9b3b-4233-8338-8ba386e2be5e" />

### Base de datos
Aunque esta maquina ya trae una base de datos voy a hacer lo que me dice el tutorial por asegurar compatibilidad y pereza para las cosas, tambien aprovecho y meto algunas
<img width="718" height="69" alt="image" src="https://github.com/user-attachments/assets/b2cbc9c7-a3c9-4fa2-ad3d-8d41e4f4a508" />


<img width="720" height="109" alt="image" src="https://github.com/user-attachments/assets/6383e698-3e9e-4553-86c4-1bb3ac58ed83" />

### Descarga e instalacion de Wordpress
Descargamos el comprimido que contiene el aplicativo de Wordpress desde su pagina oficial
<img width="711" height="422" alt="image" src="https://github.com/user-attachments/assets/f084f4aa-eb8b-4a56-b44b-62379c3a9315" />
Hacemos que la carpeta que contiene wordpress sea la carpeta que el servidor utilizar
<img width="629" height="25" alt="image" src="https://github.com/user-attachments/assets/9301684a-ac67-4465-86d7-811a3b33bba6" />



## Configuracion
### Configuraciones de la base de datos
<img width="530" height="26" alt="image" src="https://github.com/user-attachments/assets/b5be475a-4ad9-4aaf-aa44-3a76ecb26577" />
Entramos a la base de datos y aplicamos algunas configuraciones
<img width="707" height="167" alt="image" src="https://github.com/user-attachments/assets/9f1a6d76-416b-4365-80a4-a2740bdde289" />

### Configuracion del servidor web
Activamos lo que necesitamos a nivel del servidor apache,segun lo que he buscado
<img width="707" height="167" alt="image" src="https://github.com/user-attachments/assets/0e5ff94c-6aba-4074-8016-f5f60eeede3e" />
### Configuracion de Wordpress
Introducimos las credenciales de nuestra base de datos en la pagina que wordpress nos proporciona
<img width="765" height="531" alt="image" src="https://github.com/user-attachments/assets/3a626e2d-65c0-400f-80c7-666129a5cfd7" />
Luego nos va a mostrar las reglas de configuracion en un archivo **wp-config.php**, diciendome que necesito crear manualmente este archivo que no puede escribirlo, no es un problema lo creo y guardo lo que me indica, de hecho esto probablemente pasa debido a un problema que no vi en este momento con los permisos y que resuelvo más adelante
<img width="765" height="531" alt="image" src="https://github.com/user-attachments/assets/8bf5ec03-339b-47cb-a32f-29223a7710c9" />
Tal y como muestro a continuacion
<img width="843" height="824" alt="image" src="https://github.com/user-attachments/assets/a4474ad4-c363-4f61-8ab1-7f2037dab343" />
#### Informacion del sitio

<img width="843" height="824" alt="image" src="https://github.com/user-attachments/assets/5073ef5f-323e-47a7-9fe3-b5b7b9d2b55e" />
### Personalizacion y toques finales

<img width="1903" height="919" alt="image" src="https://github.com/user-attachments/assets/c8f6aad6-7443-48a8-ad8d-362da593c7c6" />

#### Wordpress con el tema activado
<img width="1903" height="919" alt="image" src="https://github.com/user-attachments/assets/6ebba131-6565-4636-abef-cf75e8d5f1e1" />


## Necesario, dar permisos a la carpeta donde se encuentra Wordpress
Es necesario para que los plugins y temas no den problemas al descargarse
<img width="1903" height="919" alt="image" src="https://github.com/user-attachments/assets/2404a280-90fc-43ee-84bb-2a43f4a170cd" />






