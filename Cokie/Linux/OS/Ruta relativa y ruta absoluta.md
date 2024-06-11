## Buscar con Grep
- Buscar una cadena dentro de un archivo ➜ `grep [term-to-search][source-file-to-search]`
- Búsqueda que no distingue entre mayúsculas y minúsculas dentro de un archivo ➜ `grep -i [term-to-search][source-file-to-search]`
- Buscar líneas que no coincidan dentro de un archivo ➜ `grep -v [term-to-search][source-file-to-search]`
- Búsqueda recursiva dentro de un directorio ➜ `grep -r [term-to-search][path-to-directory-to-search]`
- Varias búsquedas dentro de un archivo ➜ `grep -E "[first-term-to-search|second-term-to-search]"[source-file-to-search]`
- Contar los resultados de la búsqueda ➜ `grep -c [term-to-search][source-file-to-search]`
- Mostrar el nombre de los archivos coincidentes ➜ `grep -l [term-to-search][matching-files-to-search]`
- Más información sobre grep ➜ `man grep`