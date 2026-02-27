# Permisos en Linux

## ¿Qué es un usuario?

Un usuario es una cuenta que permite a una persona acceder al
sistema Linux con credenciales propias y permisos específicos.

## ¿Qué es un grupo?

Un grupo es un conjunto de usuarios que comparten permisos 
sobre archivos y directorios.

## ¿Cómo funciona chmod?

El comando chmod permite cambiar los permisos de lectura (r),
escritura (w) y ejecución (x) de archivos y directorios.

## ¿Qué significa 770?

El número 770 significa:

- 7 → lectura, escritura y ejecución para el propietario
- 7 → lectura, escritura y ejecución para el grupo
- 0 → ningún permiso para otros usuarios

## ¿Qué hace chown?

El comando chown permite cambiar el propietario o 
el grupo de un archivo o directorio.

## Creación de usuarios

Se crearon los usuarios dev1 y sup1 utilizando el comando:

sudo adduser nombre_usuario

## Creación de grupos

Se crearon los grupos developers y supporting con:

sudo groupadd nombre_grupo

## Cambio de permisos

Se asignaron permisos 770 a los directorios development y 
support para restringir el acceso únicamente al grupo 
correspondiente.
