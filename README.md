<div id="top"></div>
<div align="right">

[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

</div>

<br/>
<div align="center">
  <a href="https://github.com/ricurdinola/docker-inverse-proxy">
    <img src="readme/proxy.png" alt="Logo" width="500" height="200">
  </a>

<h3 align="center">Inverse Proxy</h3>
  <p align="center">
    Template de un Proxy Inverso NGINX con interfaz gráfica.
    <br />
    <br />
    <a href="https://nginxproxymanager.com/">Sitio Web</a>
    ·
    <a href="https://github.com/NginxProxyManager/nginx-proxy-manager">Repositorio Origen </a>
    ·
    <a href="https://github.com/NginxProxyManager">Autor</a>
    ·
    <a href="https://nginxproxymanager.com/guide/">Docs</a>
</p>
</div>

## Utilizando el Stack
A continuación, se describe brevemente la utilización del proyecto.

### Pre-requisitos
Solo es necesario tener instalado el [Docker](https://www.docker.com/products/docker-desktop) y el [Docker Compose](https://docs.docker.com/compose/install/)

### Configurar el ambiente
En el directorio raíz, existe un archivo .env, el cual contiene los siguientes parámetros configurados.

#### Stack Options
* `COMPOSE_PROJECT_NAME`: Es el nombre del stack de contenedores que se generarán.

### Instalar el ambiente
<p>Una vez cambiado los parámetros deseados, se debe ejecutar el archivo `build.sh`</p>
<p>Se publicaran 3 puertos. </p>

* El puerto 80 y 443 es para recibir las solicitudes exteriores.
* El puerto 81 es para la administración del proxy

<p>
Las credenciales por defecto son:
</p>

* Email:    admin@example.com
* Password: changeme

## Licencia
De acuerdo al proyecto original, distribuido bajo Licencia MIT. Para más información, ver el archivo
[LICENSE](https://github.com/ricurdinola/docker-inverse-proxy/blob/main/LICENSE)

<p align="right"><a href="#top">Ir al Inicio</a></p>

## Contacto
Ricardo Urdinola - ricurdinola@gmail.com - [Mis Repositorios](https://github.com/ricurdinola?tab=repositories)

<p align="right"><a href="#top">Ir al Inicio</a></p>

## Agradecimientos
Este repositorio es simplemente un template a fin de ejecutar el proyecto origen. 
Agradecimientos especiales al autor del proyecto original, [NginxProxyManager](https://nginxproxymanager.com/).

<p align="right"><a href="#top">Ir al Inicio</a></p>

[license-shield]: https://img.shields.io/github/license/ricurdinola/docker-lamp-stack?style=for-the-badge

[license-url]: https://github.com/ricurdinola/docker-inverse-proxy/blob/main/LICENSE

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555

[linkedin-url]: https://www.linkedin.com/in/urdinolaricardo/
