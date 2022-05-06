# datos-genero
Datos para el Proyecto de Estadísticas de Género

## Descripción
Estos son los archivos usado en el Tablero Estadístico de Género COVID-19 en México. Los catálogos son lo que provee la Secretaría de Salud en su diccionario de datos.

## Archivos
En Tablero usa tres archivos.

### pos_sexo_fecsin.csv
En esta tabla están los totales por día de casos positivos por sexo y por fecha de síntomas.
Cada renglón es un día donde hubo casos reportados por fecha de síntomas y por sexo.

### pos_sexo_fecsin_residencia.csv
En esta tabla están los totales por día de casos positivos por sexo, por fecha de síntomas, y por entidad de residencia.

### pos_sexo_fecsin_resid_acum_sexo.csv
Esta tabla es similar a pos_sexo_fecsin_residencia.csv. Difiere en que en esta tabla hay un renglón por cada combinación de fecha donde al menos se reportó un caso positivo, por cada una de las 32 entidades en México, y por cada sexo con datos acumulados del día anterior si no hubo casos para una entidad o sexo en particular. Esto permite una estructura cuadrada donde se puede consultar un día y una entidad dentro y se obtiene el acumulado y totales hasta la fecha. En las tablas anteriores si no hay casos reportados en una combinación dada de fecha, sexo y entidad, no existirá un renglón para esa combinación.

## tbl_defun_sexo_residencia.csv
En esta tabla hay un registro por cada grupo fecha de defunción, sexo, entidad de residencia, municipio de residencia, y grupo de edad donde hubo alguna defunción. 

## positivos_residencia_edad.zip
Este es un archivo comprimido de un csv donde cada renglón es un grupo de fecha de síntomas, entidad de residencia, municipio de residencia, sexo y grupo si es que hubo al menos un caso positivo para el grupo dado, con el total de casos.

## Diccionario datos SSA COVID-19
https://datosabiertos.salud.gob.mx/gobmx/salud/datos_abiertos/diccionario_datos_covid19.zip

## Sitio web

https://sites.google.com/view/estadisticas-genero-covid19/inicio
