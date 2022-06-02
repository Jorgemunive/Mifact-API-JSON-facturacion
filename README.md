# Integración API para Facturación Electrónica MIFACT

*Integra tu software a la facturación Electrónica fácilmente con el API JSON de Mifact.

Para poder hacer pruebas con la API debe conectar su aplicación con nuestra plataforma MIFACT mediante APIREST en formato JSON, para ello usted tiene:

📄 DocumentacionFV_BV_NC_ND_Json.xlsx para el caso de Facturas, Boletas, Notas de Crédito y Débito

📄 DocumentacionGuiaRemisionJson.xlsx para Guías de Remisión Remitente

📄 DocumentacionRetencionJson.xlsx para Facturas Electrónicas con Retenciones y Percepciones

## Estructura para Facturas, Boletas, Notas de Crédito y Débito 
(📂 Integracion-JSON-FV-BV-NC-ND):

📂 Codigos Fuentes Varios Lenguajes: contiene ejemplo para Visual Studio C#

📂 Ejemplos JSON UBL 2_1: contiene ejemplos json armados para distintos escenarios, Factura normal, operaciones Inafectas, exonerads, exportacion etre otras, anular documento, ver estados, ver PDF, XML y CDR.

📄 Documentacion-FV-BV-NC-ND-JSON.xlsx: contiene TAGS que soportan el servicio API, que siginifica cada TAG y restricciones que tiene, tambien contiene los CATALOGOS de SUNAT, respuesta del servicio API y su tratamiento.

📄 URLs_PRUEBAS.txt: contiene las URL de pruebas, el token de conexión y un RUC de pruebas, cuando termine de hacer sus pruebas debe de cambiar a una URL de producción, cambiar el token por cada RUC (emisor).


## Estructura para Guia de Remisión Remitente
(📂 Integracion-JSON-GuiaRemision):

📂 Ejemplos Archivos JSON: contiene ejemplos JSON armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar PDF.

📄 DocumentacionGuiaRemisionJson.xlsx: contiene que tags soporta el servicio API, que siginifica cada tag y que restricciones tiene, tambien contiene los catalogos de SUNAT, respuesta del servicio API y su 

📄 URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor).


## Estructura para Facturas con Retenciones y Percepciones
(📂 Integracion-JSON_Retenciones-Percepciones)

📂 Ejemplos Archivos JSON: contiene ejemplos JSON armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar 
    
📄 DocumentacionRetencionJson.xlsx: contiene que tags soporta el servicio api, que siginifica cada tag y que restricciones tiene, tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

📄 URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor). 



El servicio de integración para CONSULTA RUC es gratis para nuestros partners autorizados, si ya eres partner solicíta tus credenciales  en soporte@mifact.net.


----
----
# apijson
Integración api para software de terceros con la plataforma mifact
Para poder hacer las pruebas debera conectar su aplicacion con nuestra plataforma mifact mediante el apirest bajo el formato Json, para ello usted tiene un excel llamado DocumentacionFV_BV_NC_ND_Json.xlsx para el caso de facturas, boeletas, notas de credito y debito y DocumentacionGuiaRemisionJson.xlsx para guia de remision remitente.
DocumentacionRetencionJson.xlsx para retenciones

Estructura para Facturas, Boletas, Notas de creedito y Debito (carpeta: integracionConJson_FV_BV_NC_ND):

    Carpeta Codigos Fuentes Varios Lenguajes: contiene ejemplo para lenguaje Visual Studio C#

    Carpeta Ejemplos Archivos JSON UBL 2_1: contiene ejemplos json armados para distintos escenarios, Factura normal, operaciones Inafectas, exonerads, exportacion etre otras, anular documento, ver estados, ver PDF, XML y CDR.

    Archivo DocumentacionFV_BV_NC_ND_Json.xlsx: contiene que tags soporta el servicio api, que siginifica cada tag y que                      restricciones tiene,    tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

    Archivo URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor).


Estructura para Guia de remision Remitente (carpeta integracionConJson_GuiaRemision):
    Carpeta Ejemplos Archivos JSON: contiene ejemplos json armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar pdf.

    Archivo DocumentacionGuiaRemisionJson.xlsx: contiene que tags soporta el servicio api, que siginifica cada tag y que            restricciones tiene,    tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

    Archivo URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor). 

Estructura para Retenciones (integracionConJson_RetencionesPercepciones):
    Carpeta Ejemplos Archivos JSON: contiene ejemplos json armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar pdf.

    Archivo DocumentacionRetencionJson.xlsx: contiene que tags soporta el servicio api, que siginifica cada tag y que            restricciones tiene,    tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

    Archivo URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor). 


El servicio de integración para consulta RUC es gratuito para nuestros partners autorizados, si usted ya es nuestro parnert, solicite las credenciales para el servicio de consulta RUC.

----
----

# Dillinger
## _The Last Markdown Editor, Ever_

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Dillinger is a cloud-enabled, mobile-ready, offline-storage compatible,
AngularJS-powered HTML5 Markdown editor.

- Type some Markdown on the left
- See HTML in the right
- ✨Magic ✨

## Features

- Import a HTML file and watch it magically convert to Markdown
- Drag and drop images (requires your Dropbox account be linked)
- Import and save files from GitHub, Dropbox, Google Drive and One Drive
- Drag and drop markdown and HTML files into Dillinger
- Export documents as Markdown, HTML and PDF

Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
