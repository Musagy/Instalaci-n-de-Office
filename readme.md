# Guía de instalación de Office (Gratuita)
> Si el repositorio es viejo o no te gusta esta configuración, puedes seguir estos pasos para tener estos archivos actualizados.
>
>Esta configuración solo tiene Excel, Word y PowerPoint.

- [Crear configuración](#crear-configuración)
- [Descarga de Setup](#descarga-de-setup)
- [Comandos para la instalación](#comandos-para-la-instalación)

## Crear configuración

Para crear un archivo de **configuración personalizado** para nosotros mismos tenemos que ir a este **[link](https://config.office.com/)**.

Acá tendremos que dar a **Crear una configuración nueva**.

> En esta podrás seleccionar varias opciones, desde el idioma, o los programas que desees instalar.

Al terminar le das a exportar y le pones un nombre.

> Te recomiendo que lo nombres `config.xml`

## Descarga de Setup 

En este paso vamos a es **[link](https://www.microsoft.com/en-us/download/details.aspx?id=49117)** e ir a **Office Deployment Tool** y darle a **Download**.

y por **ultimo** para el siguiente paso colocamos tanto el archivo de **la configuración** como el archivo `setup.exe` en una **carpeta nueva** en el **escritorio** con **un nombre sencillo.**

> Te recomiendo llamar a esta carpeta `office`

## Comandos para la instalación

Por ultimo para **ejecutar** esto, vamos a abrir un **CMD** en el **buscador de Windows**

Este por defecto estará localizado en el **usuario**, para **moverlo a la carpeta** vamos a dar estos comando en consola

> Con este nos **movemos** al escritorio
```
cd desktop
```

> Acá vamos a la **carpeta** que **creamos**.
>
> Si no es `office` **remplazalo** por el nombre que le diste.
```
cd office
```

> Y al final, **ejecutamos** el `setup.exe` con el parametro del archivo de configuración
>
> Si no es `config.xml` **remplazalo** por el nombre que le diste.
```
setup.exe /configure config.xml
```