## Bandit Level 0 
Objetivo:Encontrar la contraseña del siguiente nivel. 

Comandos utilizados: 
1. ls
2. cat

Explicación: 
1. Se listaron los archivos existentes 
2. Se accedió al único archivo que existía
3. Se encontró la contraseña del nivel 1

Contraseña obtenida:
 ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If


## Bandit Level 1 
Objetivo:Encontrar la contraseña del nivel 2 en un archivo que se llama - 

Comandos utilizados: 
1. ls
2. cat< 

Explicación: 
1. Se listaron los archivos existentes 
2. Se accedió al único archivo que existía 
3. Se encontró la contraseña del nivel 2 

Contraseña obtenida:
263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Bandit Level 2 
Objetivo:Encontrar la contraseña del nivel 3 en un archivo que se llama  --spaces in this filename-- 


Comandos utilizados: 
1. ls
2. cat -- "nombre del archivo"

Explicación:
1. Se listaron los archivos existentes 
2. Se accedió al único archivo que existía 
3. Se encontró la contraseña del nivel 3

Contraseña obtenida: 
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Bandit Level 3
Objetivo: Acceder a un archivo oculto para poder averiguar la contraseña del nivel 4

Comandos utilizados: 
1. cd
2. ls -a
3. cat

Explicación: 
1. Se accedió a una carpeta
2. Se listaron todos los archivos no importando si estaban ocultos o visibles
3. Se accedió a un archivo oculto
4. Se encontró la contraseña del nivel 4

Contraseña obtenida: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Bandit Level 4 
Objetivo: Encontrar el archivo  que contiene la contraseña del nivel 4 dentro de un grupo de archivos sabiendo que el archivo con la contraseña solo contiene texto plano                                                      

Comandos utilizados: 
1. ls 
2. cd
3. file -- *
4. cat 

Explicación: 
1. Se listaron todos los archivos no importando si estaban ocultos o visibles
2. Se acccedió a una carpeta
3. Se determinó el tipo de contenido de cada archivo en la carpeta 
4. Se accedió al archivo que contenía texto plano 
5. Se encontró la contraseña del nivel 5

Contraseña obtenida: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

## Bandit Level 5
Objetivo: Encontrar la contraseña del nivel 6 en un archivo que tiene las siguientes características: Leíble, peso de 1033 bites y no ejecutable

Comandos utilizados:
1. ls
2. cd
3. find.
4. cat

Explicación:
1. Se listaron todos los archivos
2. Se aaccedió a una carpeta
3. Se buscó un archivo que cumpliera las características que establecía el objetivo
4. Se revisó el contenido del archivo encontrado 
5. Se encontró la contraseña del nivel 6
Contraseña obtenida: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

## Bandit Level 6
Objetivo: Encontrar la contraseña del nivel 7 en un archivo que tiene las siguientes características: owned by user bandit7, owned by group bandit6 33 bytes in size

Comandos utilizados:
1. ls -a
2. find /
3. cat

Explicación:
1. Se listaron todos los archivos
2. Se buscó un archivo que cumpliera las características que establecía el objetivo 
3. Se revisó el contenido del archivo encontrado
4. Se encontró la contraseña del nivel 7

Contraseña obtenida: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

