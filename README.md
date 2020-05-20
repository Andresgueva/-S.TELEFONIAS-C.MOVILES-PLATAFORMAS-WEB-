
## PROYECTO: Aplicación en NodeJS que permita leer los datos de las Suscripciones a telefonía celular móvil


INTEGRANTES:
```
- ANDRES GUEVARRA
- KEVIN CHANGOLUISA
- MARIO SUIN
- DAVID MORALES
```
```
Requerimientos funcionales:

• La media de suscripciones de todos los países en el año especificado.
• Establecer si el valor de las suscripciones del país determinado, es mayor o menor a la media mundial.
• Los cinco países por encima del valor de suscripciones del país determinado.
• Los cinco países por debajo del valor de suscripciones del país determinado.
• El top cinco de países para el año especificado.
```
```
Requerimientos no funcionales:

La aplicación dispone de dos comandos. Independientemente del comando que se ejecute, el programa debe mostrar los resultados en la terminal (utilizar colores). Considerar las validaciones correspondientes para todos los parámetros de los comandos.
El primer comando es publicar. Este comando publicará las estadísticas en una página web básica. Se requieren de tres parámetros:

• --file -f: Permite establecer el path del archivo CSV que contiene los datos a analizar
• --country -c: Permite determinar el país a analizar a través de su código ISO 3166 ALPHA-3.
• --year -y: Permite especificar el año para el cual se requiere las estadísticas. Por defecto, 2018.

El segundo comando es guardar. Este comando almacenará los resultados de las estadísticas en un archivo json. Recibe los mismos parámetros que el comando anterior, y se adiciona la siguiente opción:

• --out -o: Establece el nombre del archivo donde se almacenará los resultados.

```IMPORTANTE INSTALAR
npm i hilados colores 
nmp i csvtojson 
npm install file-system 
`` ``` `
Ejecucion
Codigo pais: ECU
Año: 2015
Suscripciones totales para indefinidas: 12943791
La media de suscripciones de todos los países es: 345515550623
----------------- Cinco países por encima del valor de suscripciones de ECU ----------------------
Pais: Austria
Bacalao: AUT
Suscripciones: 13470623
Pais: Jordania
Bacalao: JOR
Suscripciones: 13797968
Pais: Angola
Bacalao: AGO
Suscripciones: 13884532
País: Republica Árabe Siria
Bacalao: SYR
Suscripciones: 14312271
País: Burkina Faso
Bacalao: BFA
Suscripciones: 14446897
