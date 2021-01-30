# Arquitecturas Empresariales - Laboratorio 1
En el Primer Laboratorio "Maven y GIT", se escribir� un programa para calcular la desviaci�n est�ndar y media de un conjunto de n n�meros reales. El programa debe realizar la lectura de los n n�meros reales de un archivo de texto, el cual se debe utilizar una lista enlazada o Linkedlist para almacenar los n n�meros para los respectivos c�lculos. Para esto, se debe escribir una implementaci�n propia de una lista enlazada y esta debe ser compatible con la API de colecciones de Java.
## Prerequisitos

Conocimientos basicos sobre media y desviaci�n estandar de la muestra de una poblaci�n, ademas de un lista doblemente encadenada

- Funciones
  - Calculo de la desviacion estandar.
  - Calculo de la media.


## Descarga de Repositorio

Para clonar este repositorio basta con copiar la siguiente linea en un Shell de cualquier sistema operativo

**�git clone https://github.com/Killersys/AREP-Lab1.git�**

## Instalaci�n Herramientas de Repositorio

Es recomendable tener instalado maven en su computadora para poder visualizar de una mejor manera las pruebas y compilaci�n del taller. para esto dirijase al pagina de maven y siga los pasos de instalaci�n.

**https://maven.apache.org/install.html**


Una vez que tenga maven en su computadora, dirijase a la carpeta raiz del Laboratorio 1 y para compilar el proyecto se deber introducir el siguiente comando:

**mvn package**

Para poder ejecutar el programa introduce el siguiente comando

**java -cp target/taller-1-1.0-SNAPSHOT.jar edu.escuelaing.arep.app.App**

## DOCUMENTACI�N
Para poder generar la Documentaci�n del laboratorio es necesario escribir el siguiente comando en el Interprte de Comandos.
```
mvn javadoc:javadoc
```

## Pruebas  

Se muestran los dos ejemplos que estan en el pdf del taller 

Se usan los siguientes datos (prueba por cada columna)

![tabla](images/tabla.png)

Para cada columna se deberian obtener los siguientes resultados

![resultado](images/resultado.png)


## C�digo construido por medio de Herramienta

[Eclipse](https://www.eclipse.org/) plataforma de c�digo abierto para el desarrollo de aplicaciones

## Autor

Jairo Pulido


## Licencia

GNU GENERAL PUBLIC LICENSE
