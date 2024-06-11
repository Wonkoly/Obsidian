Aprender los comandos nativos más importantes de Linux es fundamental para trabajar eficientemente en este sistema operativo. A continuación, se presenta una lista de comandos esenciales que todo usuario de Linux debería conocer, organizados por categorías:

### Navegación y Gestión de Archivos

1. **`ls`**: Lista el contenido de un directorio.
   - Ejemplo: `ls -l`

2. **`cd`**: Cambia el directorio de trabajo actual.
   - Ejemplo: `cd /home/usuario`

3. **`pwd`**: Muestra la ruta del directorio de trabajo actual.
   - Ejemplo: `pwd`

4. **`cp`**: Copia archivos o directorios.
   - Ejemplo: `cp archivo_origen archivo_destino`

5. **`mv`**: Mueve o renombra archivos o directorios.
   - Ejemplo: `mv archivo_origen archivo_destino`

6. **`rm`**: Elimina archivos o directorios.
   - Ejemplo: `rm archivo`

7. **`mkdir`**: Crea un nuevo directorio.
   - Ejemplo: `mkdir nuevo_directorio`

8. **`rmdir`**: Elimina un directorio vacío.
   - Ejemplo: `rmdir directorio`

9. **`touch`**: Crea un archivo vacío o actualiza la fecha de modificación de un archivo existente.
   - Ejemplo: `touch nuevo_archivo.txt`

10. **`find`**: Busca archivos y directorios en una jerarquía de directorios.
    - Ejemplo: `find /ruta -name "archivo.txt"`

### Visualización y Edición de Archivos

1. **`cat`**: Concatenar y mostrar el contenido de archivos.
   - Ejemplo: `cat archivo.txt`

2. **`more`**: Muestra el contenido de un archivo de forma paginada.
   - Ejemplo: `more archivo.txt`

3. **`less`**: Similar a `more`, pero con más funcionalidades.
   - Ejemplo: `less archivo.txt`

4. **`head`**: Muestra las primeras líneas de un archivo.
   - Ejemplo: `head archivo.txt`

5. **`tail`**: Muestra las últimas líneas de un archivo.
   - Ejemplo: `tail archivo.txt`

6. **`nano`, `vim`, `emacs`**: Editores de texto en la línea de comandos.
   - Ejemplo: `nano archivo.txt`

### Información del Sistema

1. **`uname`**: Muestra información del sistema.
   - Ejemplo: `uname -a`

2. **`top`**: Muestra los procesos en ejecución y el uso de recursos del sistema.
   - Ejemplo: `top`

3. **`ps`**: Muestra información sobre los procesos en ejecución.
   - Ejemplo: `ps aux`

4. **`df`**: Muestra el uso del espacio en disco.
   - Ejemplo: `df -h`

5. **`du`**: Muestra el uso del espacio en disco por archivos y directorios.
   - Ejemplo: `du -sh directorio`

6. **`free`**: Muestra la memoria libre y usada del sistema.
   - Ejemplo: `free -h`

### Gestión de Permisos

1. **`chmod`**: Cambia los permisos de archivos o directorios.
   - Ejemplo: `chmod 755 archivo`

2. **`chown`**: Cambia el propietario de archivos o directorios.
   - Ejemplo: `chown usuario:grupo archivo`

3. **`chgrp`**: Cambia el grupo propietario de archivos o directorios.
   - Ejemplo: `chgrp grupo archivo`

### Redes

1. **`ping`**: Envía paquetes ICMP a una red para comprobar la conectividad.
   - Ejemplo: `ping google.com`

2. **`ifconfig` o `ip`**: Muestra o configura interfaces de red (más reciente).
   - Ejemplo: `ifconfig` o `ip addr`

3. **`netstat`**: Muestra conexiones de red, tablas de enrutamiento y más.
   - Ejemplo: `netstat -tuln`

4. **`curl`**: Transferencia de datos desde o hacia un servidor.
   - Ejemplo: `curl http://example.com`

5. **`wget`**: Descarga archivos desde la web.
   - Ejemplo: `wget http://example.com/archivo.zip`

### Compresión y Archivado

1. **`tar`**: Trabaja con archivos comprimidos y descomprimidos.
   - Ejemplo: `tar -czvf archivo.tar.gz directorio`

2. **`gzip`**: Comprime archivos.
   - Ejemplo: `gzip archivo`

3. **`gunzip`**: Descomprime archivos.
   - Ejemplo: `gunzip archivo.gz`

4. **`zip`**: Comprime archivos en un archivo ZIP.
   - Ejemplo: `zip archivo.zip archivo1 archivo2`

5. **`unzip`**: Descomprime archivos ZIP.
   - Ejemplo: `unzip archivo.zip`

### Otros Comandos Útiles

1. **`echo`**: Muestra una línea de texto.
   - Ejemplo: `echo "Hola, mundo"`

2. **`man`**: Muestra el manual de usuario para un comando.
   - Ejemplo: `man ls`

3. **`grep`**: Busca patrones en archivos.
   - Ejemplo: `grep "patrón" archivo.txt`

4. **`sed`**: Edita texto de manera automatizada.
   - Ejemplo: `sed 's/viejo/nuevo/' archivo.txt`

5. **`awk`**: Un lenguaje de programación orientado a la manipulación de archivos de texto.
   - Ejemplo: `awk '{print $1}' archivo.txt`

### Ejemplo de Comando Complejo

Combinar comandos para realizar tareas complejas es común en Linux. Por ejemplo, buscar archivos que contienen una cadena de texto específica y luego listarlos con detalles:

```sh
grep -rl "cadena" /ruta/del/directorio | xargs ls -l
```

Este comando utiliza `grep` para buscar recursivamente archivos que contienen "cadena" y luego pasa los resultados a `ls -l` usando `xargs`.

Familiarizarse con estos comandos proporcionará una base sólida para trabajar en cualquier sistema Linux.