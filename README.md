# Lissandra

## Instrucciones de instalación
**Ubicacion:** `cd /home/utnso`

**Clonar repositorio:** 

`git clone https://github.com/sisoputnfrba/tp-2019-1c-Los-Dinosaurios-Del-Libro.git`

**Compilar proyecto:** 

    cd tp-2019-1c-Los-Dinosarios-Del-Libro
    ./setup.sh

**Creación LFS** 

    cd tp-2019-1c-Los-Dinosarios-Del-Libro/creacion_LFS/Debug
    ./creacion_LFS [cant_bloques] [size_bloques] [magic_number]   
    export LD_LIBRARY_PATH=/home/utnso/tp-2019-1c-Los-Dinosaurios-Del-Libro/global/Debug

## Ejecución de los  módulos
 LFS:

    cd LFS/Debug
    ./LFS

KERNEL:

	cd Kernel/Debug
	./Kernel

Memorias:

	cd Memoria/Debug
	./Memoria [memoria.config] [memoria.log]
	
	*memoria.config y memoria.log es la memoria principal
	*memoriaN.config y memoriaN.log para las N memorias. ( N > 0 )
	
