# Integración API para Facturación Electrónica MIFACT
# Integración API para software de terceros con la plataforma mifact

*Integra tu software a la facturación Electrónica fácilmente con el API JSON de Mifact.

Para poder hacer pruebas con la API debe conectar su aplicación con nuestra plataforma MIFACT mediante APIREST en formato JSON, para ello usted tiene:

📄 DocumentacionFV_BV_NC_ND_Json.xlsx para el caso de facturas, boeletas, notas de credito y debito
📄 DocumentacionGuiaRemisionJson.xlsx para Guías de Remision Remitente
📄 DocumentacionRetencionJson.xlsx para Facturas Electrónicas con Retenciones y Percepciones

## Estructura para Facturas, Boletas, Notas de Crédito y Débito (📂 Integracion-JSON-FV-BV-NC-ND):

    📂 Codigos Fuentes Varios Lenguajes: contiene ejemplo para Visual Studio C#

    📂 Ejemplos JSON UBL 2_1: contiene ejemplos json armados para distintos escenarios, Factura normal, operaciones Inafectas, exonerads, exportacion etre otras, anular documento, ver estados, ver PDF, XML y CDR.

    📄 Documentacion-FV-BV-NC-ND-JSON.xlsx: contiene TAGS que soportan el servicio API, que siginifica cada TAG y restricciones que tiene, tambien contiene los CATALOGOS de SUNAT, respuesta del servicio API y su tratamiento.

    📄 URLs_PRUEBAS.txt: contiene las URL de pruebas, el token de conexión y un RUC de pruebas, cuando termine de hacer sus pruebas debe de cambiar  a una URL de producción, cambiar el token por cada RUC (emisor).


## Estructura para Guia de Remisión Remitente (📂 Integracion-JSON-GuiaRemision):
    📂 Ejemplos Archivos JSON: contiene ejemplos json armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar pdf.

    📄 DocumentacionGuiaRemisionJson.xlsx: contiene que tags soporta el servicio API, que siginifica cada tag y que restricciones tiene, tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

    📄 URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor).

## Estructura para Retenciones (📂 Integracion-JSON_Retenciones-Percepciones),:
    📂 Ejemplos Archivos JSON: contiene ejemplos json armados para distintos escenarios, anulaciones, enviar correo, ver estado, descargar pdf.

    📄 DocumentacionRetencionJson.xlsx: contiene que tags soporta el servicio api, que siginifica cada tag y que restricciones tiene, tambien contiene los catalogos de SUNAT, respuesta del servicio API y su tratamiento.

    📄 URLs_PRUEBAS.txt: estan las URL de pruebas, el token de conexion y un ruc de pruebas, cuando termine de hacer sus pruebas debera de cambiar la URL por la de produccion, cambiar el token por cada RUC (emisor). 


El servicio de integración para consulta RUC es gratuito para nuestros partners autorizados, si usted ya es nuestro partners, solicite sus credenciales para el servicio de consulta RUC en soporte@mifact.net.
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
