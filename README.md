# ssl-certificates
Comodo Certificate SSL Instalattion 

La instalación de certificados SSL Wildcard nos permite proteger la dirección URL de nuestro sitio web, así como también un número ilimitado de sus subdominios. Por ejemplo, un certificado Wildcard individual puede proteger www.ejemplo.cl,o bien subdominio.ejemplo.cl


STEP 1

Ingresemos al portal donde compramos nuestros certificados SSL Wildcard para descargar nuestros certificados.
Vamos a observar que nuestros certificados vienen a través de lo siguientes formatos.

ca-bundle
.crt
.p7b

A través de un archivo ZIP.

STEP 2

Estos archivos se tienen que trasladar a nuestro servidor en donde vamos a realizar la instalación del certificado.
Lo ideal es que queden en una carpeta a través del siguiente directorio cd /etc/ssl/private/*nuevacarpeta

STEP 3

Una vez creada la carpeta, depositvamos nuestros archivos y procedemos a realizar el siguiente paso.
cat certificado.crt certificado.ca-bundle > certificado.cer

STEP 4



