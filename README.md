# practicas-ISE

# Bitácora Prácticas ISE

- *Alumno:* Francisco Ferro Garrido

- *Grupo de prácticas:* B1

- *Usuario:* franferro


- *Curso:* 2025 / 2026

---

# Sesión 1 (24/09/25): 
## Creación de la bitácora
Hemos iniciado la bitacora clonando el repositorio del profesor y lo hemos editado poniendo un enlace a nuestra bitacora, para que el cambio se efectue tambien hemos visto como hacer un pull request, para que los cambios que hagamos queden reflejados en el repositorio del profesor.

## P1-L1
Tambien hemos instalado una imagen de 'debian' en virtual box, haciendo una instalacion atendida con el objetivo de crear un raid1 para tener una copia de respaldo en caso de que fuese necesaria. Todo esto desde la propia interfaz de instalacion que ofrece debian, modificando la propiedades de las particiones, su formato, etc, sin usar practicamente comandos escritos.

<img width="552" height="343" alt="Captura de pantalla 2025-10-07 193341" src="https://github.com/user-attachments/assets/e82e8a20-aed4-4d03-ad23-166f7e2c5c92" />

# Sesión 2 (01/10/2025):
## P1-L2
Hoy hemos instalado la imagen de almalinux en virtual box y a traves de lineas de comandos hemos creado nuestro usuario y le hemos dado privilegios editando un archivo con el comando 'visudo'.

Después añadí un nuevo disco, suponiendo que la carpeta /var, necesitaba más espacio. Preparé ese disco y lo integré en el sistema con el comando vgextend.
Luego creamos new_var que es una copia de var que usaremos a partir de ahora para que este sea independiente y borramos el /var antiguo siendo esta la nueva estructura de nuestro sistema:

<img width="892" height="212" alt="Captura de pantalla 2025-10-01 171640" src="https://github.com/user-attachments/assets/600559d6-98c8-4cc8-ac32-59357bb0f8d1" />


