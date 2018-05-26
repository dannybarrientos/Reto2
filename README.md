# Reto 2

Automatizaci�n de la p�gina de despegar haciendo uso del patr�n Screenplay y de un conector de Excel

## Requerimientos

El proyecto puede importarse en cualquier IDE de desarrollo, preferiblemente Eclipse.  Se trata de un proyecto Gradle y conviene tener instalada la �ltima versi�n, al igual que el plugin de Cucumber

### Instalaci�n

Para clonar el proyecto, ejecutar el comando:

```
git clone https://github.com/sandrabonilla/Reto2.git
```
### Driver

El driver utilizado para la prueba es el driver de chrome versi�n 2.38 <[chromedriver.exe](https://sites.google.com/a/chromium.org/chromedriver/downloads)>.  Sin embargo, es posible ejecutarlo con otros driver realizando una modificaci�n al atributo driver de la anotaci�n @Managed

## Conclusiones

* El patr�n Screenplay facilita en gran medida la reutilizaci�n de c�digo gracias a la orientaci�n a tareas
* La librer�a POI provee una implementaci�n sencilla para crear, editar y eliminar archivos de excel
* Es muy importante contar con una buena conexi�n a internet para realizar pruebas automatizadas, pues esto puede tener una incidencia muy negativa en las pruebas
* El manejo de calendarios es complejo y es muy importante llegar a una soluci�n que no dependa de la fecha actual
* Las popup y modales son elementos que pueden aumentar significativamente la inestabilidad de las pruebas, por lo que es importante contar con una buena estrategia para controlarlas
* Es importante analizar los xpath que generan los navegadores antes de utilizarlos, pues mucha veces no son adecuados