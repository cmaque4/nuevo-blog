---
title: Subida de documentos
excerpt: Aquí se muestra el proceso que aprendí para poder subir diferentes trabajos a la red, esto con ayuda de la Herramienta **`GitHub`**, la cual es la forma en que podemos subir los códigos que hagamos a la red para que sea modificado a nuestro gusto.
subtitle: 'Dos formas de subir nuestros proyectos a GitHub'
author: Carlos Puma
date: '2022-01-23'
slug: []
categories: [Git, GitHub]
tags: []
links:
- icon: youtube
  icon_pack: fab
  name: Video de Ejemplo
  url: https://www.youtube.com/watch?v=ibIMUUr616Y
---



<img src="https://universo-nintendo.com.mx/my_uploads/2021/02/Universo-Nintendo-Mushoku-Tensei-Jobless-Reincarnation-Futuro.jpg"/>

---

# Uso de Git y GitHub

Primero iniciaremos con la instalación de **`Git`** [Link de Descarga](https://git-scm.com/) la cual es una herramienta que nos ayudará a conectar nuestros trabajos a **`GitHub`** es muy simple su descargar.

### Link de Descarga

Luego de rediriginos a la pagina de **`Git`** vamos a precionar **Download for Windows**.

<img src="https://scontent.xx.fbcdn.net/v/t1.15752-9/p206x206/271357751_2111427132347224_295164844886427551_n.png?_nc_cat=102&ccb=1-5&_nc_sid=aee45a&_nc_ohc=sqhw6L4TDRUAX84lbOp&_nc_ad=z-m&_nc_cid=0&_nc_ht=scontent.xx&oh=03_AVIEQc5Jqsz72jcWW5yR9Wk-BuiLb1rwE8qy9YHAnIm-KQ&oe=6212D7E6" width="65%" style="display: block; margin: auto;" />


**Paso 1**: Al finalizar este proceso, nos vamos a dirigir a nuestro Rstudio y vamos a abrir un nuevo proyecto **File - New Proyect - Version Control - Git**, si esta parte nos permite colocar un **Repository** en git, es porque ahora podemos trabajar con nuestro **`GitHub`**

**Paso 2**: Luego de obtener nuestro git, nos vamos a crear una cuenta en **`GitHub`** la cual es muy sencilla, solo nos vamos a su [página](https://github.com/) y nos creamos nuestra cuenta. 
 
<img src="https://cdn.fbsbx.com/v/t59.2708-21/270166893_1061948367982531_5140137383535741867_n.gif?_nc_cat=103&ccb=1-5&_nc_sid=041f46&_nc_eui2=AeFMJ5e3-hSUnK367xml7QGrSOCRPXvy7a5I4JE9e_LtrvCWNQqpeeQiJLIBSJ15gPl_s2TcV0o4aOKcYAEsDImJ&_nc_ohc=Bc4oZm7b8BcAX8Eycqa&_nc_ht=cdn.fbsbx.com&oh=03_AVLLnESA56BvmUqOyKsO9rLdgL-mbj2E_QuTfuzy3C2Erw&oe=61F23070" width="100%" style="display: block; margin: auto;" />


**Paso 3**: Cuando ya tengamos nuestra cuenta, vamos a crear un repositorio, el cual vamos a poder el nombre que queramos, puede ser publico o privado (es nuestra decisión) y por ultimo darle clic a README y creamos nuestro repositorio

**Paso 4**: Luego vamos a ir a **Code** y copiamos ese link, en nuestro **GIT** de nuestro Rstudio, despues le damos **Open a new sesion** y creamos nuestro Proyecto, el cual va a estar conectado y podremos hacer los cambios que querramos sin que nuestro código se pierda.

<img src="https://cdn.fbsbx.com/v/t59.2708-21/272709524_300142215297915_5071314379844479178_n.gif?_nc_cat=106&ccb=1-5&_nc_sid=041f46&_nc_eui2=AeET3aitqoTJEg9miNupwC696jynuXwFaGfqPKe5fAVoZ1hNr0E3SLvfncdA6NublP0U7jDY5JHIiUVx1zRrYJKb&_nc_ohc=yqKGpuJJ1KoAX8uTqsR&_nc_ht=cdn.fbsbx.com&oh=03_AVIefTNDiF2JTqGt-foezusXDYBERgOna6hKaLbsv3Kh6Q&oe=61F108F3" width="100%" style="display: block; margin: auto;" />

### Otra forma de hacerlo

Podemos tener nuestro proyecto ya realizado sin esa conexión con nuestro Github, y bueno realizar el procedimiento anterior puede ser muy pesado para hacerlo. Entonces para que nuestro trabajo se suba como un repositorio a nuestro GitHub solo debemos colocar los siguientes códigos 


```r
usethis::use_git()
usethis::use_github()
```

- Aquí vamos a utilizar primero **`usethis::use_git()`** el cual nos a mostrar diferentes alternativas, y debemos aceptar o colocar de forma positiva las acciones, luego se va a conectar y volver a cargar nuestro Rstudio
- Luego vamos a colocar **`usethis::use_github()`**, esta función nos a crear un nuevo repositorio en nuestro GitHub y podremos ver subidos nuestros archivos, y podemos hacer los cambios que queramos, con los pasos que están en el **Vídeo de Ejemplo**. 

#### Enlaces de Referencias

1. [Beatriz Milz](https://beatrizmilz.com/talk/2021-blogdown-apero/) coloca que la sección de código usado
2. [Alison Hill](https://www.youtube.com/watch?v=yXFu_upDL2o) en su vídeo de creación de un blog
