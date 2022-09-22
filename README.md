# Introduccion-a-Python
Este repositorio tiene los programas de introduccion a  Python3
1. CONFIGURACION DEL ENTORNO PARA PYTHON

Se realiza la instalacion de python con el comando:
* sudo apt-get install python3
se verifica la versiòn con : python --version
Se muestra una captura de pantalla de tal instalacion.
![image](https://user-images.githubusercontent.com/111370930/191139643-c61c9378-6753-4579-935c-2968c856604a.png)

Se observa tambien un primer ejemplo compilado con python de hola.py
donde se abre el editor nano y posterioremtente tambien se compila.
![image](https://user-images.githubusercontent.com/111370930/191139610-333b78f9-fec1-400f-8bfa-9a6cfc718bf8.png)

Dentro del editor Visual Code instalamos los complementos de python3:

![image](https://user-images.githubusercontent.com/111370930/191140255-82a6cabc-60c0-4907-8265-bc950316672d.png)

Siguiendo con la configuracion, nos dirigimos a la siguiente pagina para la descarga de Anaconda: 
https://www.anaconda.com/products/distribution.

Don descargamos la version: Anaconda3-2022.05-Linux-x86_64.sh
![image](https://user-images.githubusercontent.com/111370930/191139915-2ec4f9bb-9ac9-4779-8047-b4705127809c.png)
 E instalamaos este complemento con los comandos:
 
gustavo@gustavo-VirtualBox:~/Downloads$ bash Anaconda3-2022.05-linux-x86_64.sh
y posterioermente  ala instalacion de jupyter:

gustavo@gustavo-VirtualBox:~/Downloads$ sudo apt-get install jupyter

 Despues de la instalacion de Jupyter, se procede al desarrollo de de los ejemplos de la plataforma de codigoIoT:
1.- Ejemplo donde se insertan variables desde teclado.


![image](https://user-images.githubusercontent.com/111370930/191407406-19b0230d-d3aa-4e29-9294-23c98c3c2d5d.png)


2.- Ejemplo con if-else
![image](https://user-images.githubusercontent.com/111370930/191407738-9e4a5978-828e-4488-8a70-835d52000969.png)


3.- Ejemplo if: Diferente de cero
![image](https://user-images.githubusercontent.com/111370930/191408072-f9375006-31c7-4be7-b0b0-3ed012ba182f.png)


4.- Ejemplo: Numero diferente de cero o =  a 0
![image](https://user-images.githubusercontent.com/111370930/191408229-d24be1b8-4d35-4256-bded-99b28150c642.png)


5.- Ejemplo de ciclos: Bit de paridad
![image](https://user-images.githubusercontent.com/111370930/191408390-ad20c17f-f78e-43f5-b94c-a290a172940e.png)


6.-Ejemplo de Valor Maximo y Minimo.
![image](https://user-images.githubusercontent.com/111370930/191408787-87298962-718b-4a85-8028-78ea8f91a60b.png)


7.-Ejemplo: Multiplos hasta N.
![image](https://user-images.githubusercontent.com/111370930/191408901-0eacc096-c1a7-4256-89a1-e4d9f51d3b47.png)


8.- Ejemplo: Funcion Rectangulo (Paso de parametros).
![image](https://user-images.githubusercontent.com/111370930/191416900-4fdfebaa-e2bc-4ac8-aee5-7089980d7122.png)
![image](https://user-images.githubusercontent.com/111370930/191417045-1515f942-594f-4d9d-b88c-e949cc14e9dc.png)


9.- Ejemplo  Sucesion (Retorno de valores)
![image](https://user-images.githubusercontent.com/111370930/191416976-ec7e333f-b401-42f7-a6a6-80baed3fdedd.png)

------------------------REGRESIONES LINEALES ---------------------

Siguiendo con las funciones se realizan las funciones de las regresiones lineales utilizando puntos aleatorios y calculados con
los minimos cuadrados.
10.- El primer ejemplo de regresion lineal es el siguiente:
![image](https://user-images.githubusercontent.com/111370930/191803567-a0019f5f-a81b-47a7-a22c-e6c018d0128f.png)
En donde se crea llos valores aleatorios y se normalizan mediante la predicion/objetivo.

11.- En el segundo ejemplo observamos la traza o linea de regresion lineal utilizamos el paquete: from sklearn.linear_model import LinearRegression 
![image](https://user-images.githubusercontent.com/111370930/191804138-b5bfb8a5-163b-45f7-bf4f-7a8661ad23c6.png)

12. Y por ultimo observamos el ejemplo de la regresion lineal y polinomica grupadas.
![image](https://user-images.githubusercontent.com/111370930/191804558-896e6962-ed80-4492-943c-f952781a589c.png)

Es importante señalar que para la ejecucion de los paquetes import numpy, pandas, etc..
Se deben realizar los siguientes comandos:

sudo apt-get install python3-numpy

sudo apt-get install python3-matplotlib

sudo apt-get install python3-pandas

sudo apt-get install python3-sklearn

Liga: 
https://github.com/Gustavo-MA/Introduccion-a-Python

Autor: Gustavo M-A.
Email: gustavo.medina@uaem.edu.mx








