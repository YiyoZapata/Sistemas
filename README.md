# Sistemas

###EJERCICIO 01
##Yiyo Zapata Martinez

Uso un emulador de powershell porque uso como sistema operativo Ubuntu 20.04.

#1.- Crea la siguiente estructura de carpetas:

-MD APLI PROG VARIOS
-CD APLI
-MD WORD ACCESS EXCEL
-CD ..
-CD PROG
-MD BASIC PASCAL FROTRAN
-CD ..
-CD APLI/WORD
-MD TEXTOS NOTAS
-CD ..
-CD EXCEL
-MD TABLAS INFO

#2.- Sitúate en la carpeta TABLAS

-CD ./APLI/EXCEL/TABLAS/

#3.- Vuelve a la carpeta raíz

-CD ../../

#4.- Muestra el contenido de la carpeta PROG

-DIR POG

#5.- Borra la carpeta PASCAL

-RD PASCAL

#6.- Sitúate en la carpeta VARIOS y desde allí crea una nueva carpeta dentro de WORD llamado
PRACT

-CD VARIOS
-MD PRACT



#7.- Sitúate en PRACT y desde allí muestra el contenido de la carpeta EXCEL

-CD ./APLI/WORD/PRACT/
-DIR /HOME/YIYO/PRACTICAPOWERSHELL/APLI/EXCEL/

#8.- Desde TABLAS muestra el listado de archivos y carpetas de la carpeta raíz

-CD TABLAS
-DIR /HOME/YIYO/PRACTICAPOWERSHELL



#9.- Sitúate en la carpeta APLI y desde allí crea una subcarpeta llamada AGENDA dentro de
VARIOS

-CD APLI
-MD /HOME/YIYO/PRACTICAPOWERSHELL/VARIOS/AGENDA

#10.- Borra la carpeta EXCEL

-RD /HOME/YIYO/POWERSHELL/APLI/EXCEL/

#11.- Desde la carpeta raíz, crea en ella una subcarpeta llamada NUEVO

-MD /HOME/YIYO/POWERSHELL/APLI/NUEVO

#12.- Desde PRACT muestra el contenido de WORD

-DIR /HOME/YIYO/POWERSHELL/APLI/WORD/
