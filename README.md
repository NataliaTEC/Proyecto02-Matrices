
# Proyecto 04 - Controlador interactivo
<img src=RaspberryPi.png alt="Raspberry Pi" width="50" height="50"> <img src=python3.png alt="Python3" width="50" height="50">
### IC-3101 Arquitectura de Computadoras
------------

#### Integrantes: 
- Sergio Montoya Badilla **| 2023344598** 
- Alice Arias Salazar **| 2023104639**
- Natalia Granados Rosales **| 2021144286**
- Deislher Sánchez Funez **| 2023032794**

------------
#### Descripción del juego

"Buscatesoros" es un juego de exploración donde el jugador debe encontrar todos los tesoros escondidos en un mapa, evitando pisar minas. El jugador puede moverse en cuatro direcciones (arriba, abajo, izquierda, derecha) y cavar en su posición actual para buscar tesoros. El juego se basa en una matriz que representa el mapa, donde los tesoros y las minas están distribuidos aleatoriamente.

------------

#### Requisitos del sistema

- Tener un **Raspberry Pi** físico.
- Tener mínimo una tarjeta microSD de **8GB** de almacenamiento para el correcto funcionamiento del proyecto en el **Raspberry Pi**.
- Instalar **python3**
------------
#### Objetivos del Proyecto
- **Diseñar y construir** un controlador de juego utilizando los pines GPIO de la Raspberry Pi.
- **Implementar** un juego interactivo que permita al usuario moverse, cavar y encontrar tesoros, evitando minas.

------------
#### Instalación
Para ejecutar el programa de **Buscatesoros**, por favor sigue estos pasos:
###### Clonar el repositorio:

- Abra cualquier carpeta en su pc personal y clone el repositorio mediante el siguiente comando:

   ```bash
   git clone https://git.mora.tk/sermonbadi/py4-arquitectura-de-computadores.git

Este comando descarga una copia completa del proyecto desde el enlace proporcionado a tu sistema local. Si no tienes Git instalado en tu sistema, puedes hacerlo usando un enlace de instalación que debería haber proporcionado, o buscarlo en la **[Web de Git.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)**

- Luego de Enter, espere a que termine el proceso de clonado, y busque la carpeta para verificar el contenido. Una vez verificado el contenido, copia esta carpeta en alguna llave de maya y conecta la llave al raspberry Pi y copia la carpeta en el Raspberry Pi.
------------
#### Instalación de python3

- Abra la terminal de su Raspberry Pi e ingrese el siguiente comando para asegurarse de tener todo el sistema actualizado
   ```bash
  	sudo apt-get update
	sudo apt-get upgrade

- Una vez verifiquemos que esta todo actualizado procedemos a instalar Python.
  	 ```bash
  	sudo apt install python3


------------

#### Ejecución
1. Primero buscar donde copiamos el archivo .py en nuestro Raspberry Pi, una vez encontremos el archivo tendremos que ir a esa misma dirección usando la terminal siga el siguiente comando, como ejemplo:
    ```bash
	cd Documents/PP4/SCR/main
2. Ahora que estamos en la misma carpeta podemos ejecutar el proyecto con el siguiente comando:
    ```bash
	python3 buscatesoros.py
3. Debe verse de la siguiente manera:
   
   ![image](https://github.com/user-attachments/assets/bba31b8f-26c9-4138-8138-e6d22eea405f)


------------
#### Manual del Usuario
