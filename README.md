# Lissandra - FS

A continuación todo lo necesario para la instalación y ejecución del proyecto.
## Instalación

**Clonar repositorio:** 


**Compilar proyecto:** 

    ./setup.sh

**Creación LFS** 

    ./creacion_LFS [cant_bloques] [size_bloques] [magic_number]   
    
 export LD_LIBRARY_PATH=/LISS-FS/global/Debug

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
	
