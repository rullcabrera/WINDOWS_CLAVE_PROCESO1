author: Raúl Cabrera Garcia
summary: Guía Rápida Recuperación Contraseña Windows (Deshabilitar proceso)
id: WINDOWS_CLAVE_PROCESO1
categories: codelab,markdown
environments: Web
status: Published
feedback link: Enlace github para los issue

# Guía Rápida Rec. contraseña en Windows (Deshabilitar Proceso)

## Página 1
Duration: 00:02:00

### Tenemos varias maneras desde el *CMD* o a través de las políticas locales del sistema.

* Creamos un usuario de pruebas con una clave *“user2”*, en local.
![Foto1_WClave1](img/foto1.jpg)

Positive
: Ahora abrimos un CMD como administrador. Ejecutamos lo siguiente:

![Foto2_WClave1](img/foto2.jpg)

* Iremos a comprobar que no podemos ***“restablecer contraseña”***, con *“user2”*.
![Foto3_WClave1](img/foto3.jpg)

## Página 2
Duration: 00:02:00

### Y ahora haremos lo mismo pero desde las políticas locales del sistema.

Positive
: Pulsamos *“Win Key+R”*. Escribimos *lusrmgr.msc*

* Se nos abre la ventana de *políticas locales del sistema*. Y nos vamos a:

Positive
: *Usuarios y grupos locales* → *Usuarios → usuario_elegido* → *Propiedades* → ***Desmarcamos El usuario no puede cambiar la clave*** → *Aplicar* → *Aceptar*.
Conseguimos el mismo efecto, nos saldría el mismo mensaje que en el punto anterior.

![Foto4_WClave1](img/foto4.jpg)
