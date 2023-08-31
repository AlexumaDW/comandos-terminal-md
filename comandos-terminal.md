# Comandos Terminal GitBash

## Diferencias entre CLIs y GUIs

### GraphicUserInterface:

A visual way of interacting with a computer using items such as windows, icons, and menus, used by most modern operating systems.

### CommandLineInterface:

Is a text-based user interface (UI) used to run programs, manage computer files and interact with the computer.

## Comandos:

- [pwd](#pwd)
- [whoami](#whoami)
- [help](#help)
- [clear](#clear)
- [ls](#ls)
- [cd](#cd)
- [touch](#touch)
- [mkdir](#mkdir)
- [rmdir](#rmdir)
- [rm](#rm)
- [mv](#mv)
- [cp](#cp)
- [find](#find)
- [alias](#alias)

## Comandos modo uso:

- #### **_pwd :_**
  - devuelve la ruta en la cual se esta ejecutando la terminal en ese momento.

[volver](#comandos)

- #### **_whoami :_**

  - Devuelve el usuario que esta usando la terminal en ese momento.

[volver](#comandos)

- #### **_help :_**
  - The help command is a Command Prompt command that's used to provide more information on another command.
  - Se escribe el commando que necesitamos mas información seguido de help
    - command **--help**

[volver](#comandos)

- #### **_clear :_**
  - Limpia la terminal de command.

[volver](#comandos)

- #### **_ls :_**
  - Lista los archivos del directorio en el que nos encontramos.

[volver](#comandos)

- #### **_cd :_**
  - Cambia el directorio.
  - **_cd_**
    - Cambia a la carpeta raiz.
  - **_cd .._**
    - Vuelve un directorio atras.
  - **_cd ../.._**
    - Vuelve 2 directorios atras.
  - **_cd nombre-carpeta_**
    - Entra en la carpeta del directorio actual.
  - **_cd -_**
    - regresar a la carpeta anterior.
  - **_cd carpetas con espacios_**
    - "carpeta con espacios" se agregan comillas cuando tienen espacios en blanco.

[volver](#comandos)

- #### **_touch :_**
  - touch nuevo-archivo.extension
  - Crear un nuevo archivo.

[volver](#comandos)

- #### **_mkdir :_**
  - mkdir nueva-carpeta
  - Crea una nueva carpeta.

[volver](#comandos)

- #### **_rmdir :_**
  - rmdir carpeta-vacia
  - Elimina la carpeta vacia.

[volver](#comandos)

- #### **_rm :_**
  - rm archivo.extension
  - Elimina el archivo.
  - **_rm -r nombre-carpeta-a-eliminar-con-archivos_**
    - Elimina la carpeta con todo su contenido
  - **_rm -rf nombre-carpeta-a-eliminar-con-archivos-en-ejecucion_**
    - Elimina la carpeta con todo su contenido, forzando la eliminacion y eliminando procesos.

[volver](#comandos)

- #### **_mv :_**
  - mv nombre archivo/carpeta directorio-destino
  - Mueve archivos o carpetas hacia el directorio deseado.
  - **_ mv nombre-actual.extension nombre-deseado.extension _**
    - Renombra archivos y carpetas

[volver](#comandos)

- #### **_cp :_**
  - cp nombre-archivo.extension
  - Copia archivos dentro del mismo directorio
  - **_cp nombre-archivo directorio-destino/nombre-deseado.extension_**
    - Copia archivos a otros directorios, el renombre es opcional.
  - **_cp -r nombre-carpeta directorio-deseado_**
    - Copia carpetas con y sin contenido en el directorio deseado.

[volver](#comandos)

- #### **_find :_**
  - find palabra-a-buscar.extension
  - Busca coincidencias desde el directorio actual a sus directorios descendientes.

[volver](#comandos)

- #### **_alias_ :**
  - Ver todos los alias creados.
  - **_alias nombre-del-alias="command"_**
    - Crea un alias (atajo de escritura) de un comando dado.
    - Importante el comando va pegado al = y entre "".
  - **_unalias nombre-del-alias_**
    - elimina un alias

[volver](#comandos)
