# Curso de personalizacion de linux (hack4u.io)

Este repositorio contiene los ficheros de configuracion de los paquetes que se han utilizado en el curso de personalizacion de linux de [hack4u.io](https://hack4u.io/) de la mano de s4vitar.

## Contenido del repositorio

Ficheros de configuracion de los siguientes paquetes:

- [ ] [**bspwm**](#bspwm)
- [ ] [**rofi**](#rofi)
- [ ] [**sxhkd**](#sxhkd)
- [ ] [**polybar**](#polybar)
- [ ] [**kitty**](#kitty)
- [ ] [**picom**](#picom)

### BSPWM

- [**bspwmrc**](./bspwm/bspwmrc): Fichero de configuracion de bspwm.
- [**scripts**](./bspwm/scripts/): Directorio con scripts de utilidad para bspwm.

BSPWM es un gestor de ventanas que se controla mediante eventos y que se configura mediante scripts. En este repositorio se incluyen los ficheros de configuracion de bspwm y algunos scripts de utilidad.

En este caso, como el curso está orientado a la realizacion de un entorno de trabajo para pentesting, existen varios scripts que, junto a picom, permiten visualizar ciertas cosas como IP actual, IP de HTB, etc.

### Rofi

- [**config.rasi**](./rofi/config.rasi): Fichero de configuracion de rofi.
- [**themes**](./rofi/themes/): Directorio con temas para rofi.

Rofi es un lanzador de aplicaciones y ventana de cambio de ventanas. En este repositorio se incluyen los ficheros de configuracion de rofi y algunos temas.

### SXHKD

- [**sxhkdrc**](./sxhkd/sxhkdrc): Fichero de configuracion de sxhkd.

SXHKD es un demonio que se encarga de gestionar los atajos de teclado. En este repositorio se incluye el fichero de configuracion de sxhkd.

### Polybar

- [**config**](./polybar/config): Fichero de configuracion de polybar.
- [**scripts**](./polybar/scripts/): Directorio con scripts de utilidad para polybar.
- [**colors.ini**](./polybar/colors.ini): Fichero con los colores utilizados en polybar.
- [**fonts**](./polybar/fonts/): Directorio con las fuentes utilizadas en polybar.
- [**current.ini**](./polybar/current.ini): Fichero con la configuracion de las barras actuales.
- [**launch.sh**](./polybar/launch.sh): Script para lanzar polybar.
- [**workspace.ini**](./polybar/workspace.ini): Fichero con la configuracion de las workspaces.

Polybar es una barra de estado que se puede personalizar mediante ficheros de configuracion. En este repositorio se incluyen los ficheros de configuracion de polybar y algunos scripts de utilidad.

Polybar permite mostrar informacion en la barra de estado, como la fecha y hora, el uso de CPU y memoria, el estado de la bateria, etc. En este caso solo se ha desplegado la barra de los workspaces, algunos scripts, la barra de la fecha y hora y una barra pequeña para poder apagar el sistema.

### Kitty

- [**kitty.conf**](./kitty/kitty.conf): Fichero de configuracion de kitty.
- [**color.ini**](./kitty/color.ini): Fichero con los colores utilizados en kitty.

Kitty es un emulador de terminal que se puede personalizar mediante ficheros de configuracion. En este repositorio se incluyen los ficheros de configuracion de kitty.

### Picom

- [**picom.conf**](./picom/picom.conf): Fichero de configuracion de picom.

Picom es un compositor que se puede personalizar mediante ficheros de configuracion. En este repositorio se incluye el fichero de configuracion de picom.

Picom permite añadir efectos de transparencia, sombras, etc. En este caso se ha configurado para añadir sombras y redondez a las ventanas.
