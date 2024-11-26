
### IC-3101 Arquitectura de Computadoras
------------

#### Integrantes: 
- Sergio Montoya Badilla **| 2023344598** 
- Alice Arias Salazar **| 2023104639**
- Natalia Granados Rosales **| 2021144286**
- Deislher Sánchez Funez **| 2023032794**

------------
#### Descripción

El proyecto tiene como objetivo desarrollar un juego de búsqueda de tesoros interactivo diseñado para ejecutarse en una interfaz de línea de comandos utilizando lenguaje ensamblador de **ARM 64 bits**. Este juego busca desafiar a los jugadores a encontrar tesoros ocultos en un mapa a través de pistas (frio, caliente).

------------

#### Tecnologías Utilizadas
El desarrollo se realizará en lenguaje ensamblador **ARM** de 64bits, utilizando **Raspbian OS** en **Raspberry Pi** o mediante el emulador **QEMU**.

------------
#### Objetivos del Proyecto
- **Implementar** algoritmos para la generación aleatoria de mapas y la colocación de tesoros utilizando matrices.
- **Desarrollar** habilidades de pensamiento crítico y estratégico en los jugadores mediante la resolución de pistas para localizar los tesoros.
- **Crear una experiencia** de juego interactiva y envolvente mediante el uso de comandos de texto para explorar y descubrir tesoros ocultos.

------------
#### Instalación
Para ejecutar el programa de **Treasure Grid**, por favor sigue estos pasos:
###### Clonar el repositorio:

- Abra QEMU y clone el repositorio mediante el siguiente comando:

   ```bash
   git clone https://git.mora.tk/desanchez/proyecto-3-treasure-grid.git

Este comando descarga una copia completa del proyecto desde el enlace proporcionado a tu sistema local. Si no tienes Git instalado en tu sistema, puedes hacerlo usando un enlace de instalación que debería haber proporcionado, o buscarlo en la **[Web de Git.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)**

- Luego de enter, espere a que termine el proceso de clonado, e ingrese a la carpeta clonada con el comando
    ```bash
      cd proyecto-3-treasure-grid

------------

#### Ejecución
1. Primero ensamble el programa con el comando
    ```bash
	as -o prueba.o *.s
2. Luego, enlace el programa con el comando
    ```bash
	ld -o prueba prueba.o
3. Por último, ejecute el programa con el comando
    ```bash
	./prueba

------------
#### Manual del Usuario
