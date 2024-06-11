La pagina de los juego es -> https://overthewire.org/wargames/bandit/

## Level 0 -> Level 1
Conectarse por [[SSH]] a bandit.labs.overthewire.org en el puerto 2220, usando el las credenciales `bandit0` con la contraseña `bandit0`. 

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

El parametro -p nos indica el numero de puerto por en donde nos queremos conectar.

## Level 1 -> Level 2
## Level 2 -> Level 3
## Level 3 -> Level 4
## Level 4 -> Level 5
La constraseña al siguiente nivel se encuentra el alguno de los 10 archivos del directorio inhere. Para localizar el archvico con la contraseña debemos de ver cuales.

## Level 5 -> Level 6
Para obtener accesos se tomo en cuenta las siguientes características del archivo: `human-readable`, `1033 bytes in size` y `not-executable`.
Se utiliza el comando [[find]] con las opciones -type, -executable, -size y -readable.

```bash
pwd
> /home/bandit5

//se aplico un find con los argumento que describen lo anterior
find . -type f -readable ! -executable -size 1033c
> [Constraseña al siguiente bandit]
```

## Level 6 -> Level 7


