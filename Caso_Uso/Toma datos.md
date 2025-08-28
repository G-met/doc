# Toma de Datos 
El objetivo del toma datos es capturar la informacion al momento de la calibracion o verificacion.

### Prerequisitos
  1. El equipo debe existir.
  1. Debe tener alguna progracion.
  1. debe existir un responsable por la ejecucion del proceso de calibracion o verificacion.
  
### Proceso

El toma datos varia de acuerdo a la magnitud, y tiene campos muy variados.

Lo que es comun para cada caso es:
  1. #### Prueba inicial
     Son los Datos inciales que se toman al equipo para confirmar si su estado es apto para realizar el proceso de calibracion, y ademas ratificar que esta dentro del EMP.
     De ser apto se procede con el proceso de calibracion o verificacion, segun el caso.
     Para nuestro caso si la prueba preliminar es satisfactoria, no se requiere de realizar ajustes.
     De no ser apto se procede a realizar los ajustes por el personal tecnico autorizado para este fin.

  1. #### Prueba Final
     Una vez realizados los ajustes se procede a realizar la prueba final donde se capturan los datos para confirmar que el equipo es apto para el proceso de calibracion o verificacion segun el caso.
     
  1. #### Resultado de la verificacion.
     En este punto se capturan los datos de todo el proceso de verificacion, de acuerdo a la norma utilizada para ese fin.
     Con base en esta informacion es que se declara si el equipo es conforme, se calcula el error y la incertidumbre.
     Con la informacion obtenida se puede generar el reporte de calibracion.

  1. #### Observaciones.
     En este campo se describen todas las anotaciones pertinentes que se encontraron al memento de efectuar el proceso de calibracio o verificacion, segun el caso.

  1. #### Responsable
     En esta opcion se debe colocar la persona responsable de ejecutar el proceso de calibracion o verificacion, segun el caso.

     

Vamos a describir como seria para cada caso.

### Toma Datos PH
Para el caso del ph, cuando ingrese el codigo del equipo este me debera traer los datos basicos que se encuentran registrados tales como:
1. Descripcion del Equipo
1. Marca
1. Modelo
1. Serie
1. Ubicacion
1. Unidad de Medida
1. Resolucion
1. EMP ( error maximo permitido ).

Una vez que he validado que el equipo es el se requiere para la calibracion y que los datos son los correctos, se debe seleccionar una fecha de la lista de programacion que existe para ese equipo.

Despues se debe ingresar las caracteristicas del patron. Para el caso de ph se utilizaran 3 MRC (material de referencia certificado) en los valores 4, 7, y 10 ph.

Para cada patron se debe seleccionar el codigo del patron a utilizar y este me debe traer los datos del lote y la fecha de vencimiento del patron.

Si la fecha de vencimiento del patron esta vencida, me debe sacar una alerta que el patron esta vencido y que no es posible continuar con el proceso. Por el contrario si la fecha de vencimiento esta correcta se debe continuar con el proceso.

### Condiciones Ambientales
En estos campos dse deben consignar los datos de la temperatura maxima y minima que hubo en todo el proceso, lo mismo con la humedad relativa.

## Prueba Preliminar
La prueba preliminar nos sirve para establecer el estado actual del equipo para establecer si esta apto pera el proceso de calibracion o verificacion dado el caso.

Se hara una medicion con cada patro ( 4, 7 y 10 Ph ), los datos que se deben consignar son:
1. El valor del material de referencia a 25 grados centigrados.
2. La temperatura actual del material de referencia.
3. Con los datos anteriores se realiza la correcciondel material de referencia por temperatura.
4. Valor indicado por el equipo evaluado.
5. El milivoltaje que indica el equipo de medicion paara la lectura de ph.
6. Con estos Datos se calcula el error.

Con esta informacion se realiza la evaluacion teniendo como referencia el EMP ( error maximo permitido ), que se ha establecido para el equipo en evaluacion.
Si el error esta dentro del EMP, el equipo se envuentra apto para realizar el proceso de calibracion.
Este proceso se repite para cada valor de ph.

En caso de que el equipo bajo prueba no cumpla con el criterio de evaluacion ( que este dentro del EMP ), se debe proceder a informar al cliente, quie debera realizar los ajustes que se requieran para que el equipo quede apto para su evaluacion.

Una vez que al equipo se le hayan realizado las actividades necesarias para que quede apto, se realizara una nueva prueba para evaluar que los procedimientos fueron los adecuados.

Esta prueba se capturara en los campos de prueba final, y si el equipo esta apto, ya se podra realizar el proceso de calibracion o verificacion segun sea el caso.

En el caso de que la prueba Preliminar sea satisfactoria, se podra realizar el proceso de calibracion.

### Prueva de la Calibracion.

Esta sera la prueba donde se evaluara si el equipo cumple de acuerdo .......

Para este caso para cada valor de ph del MRC ( Material de referencia certificado ) se tomaran tres lecturas consignando los mismos valores que se tomaron en la prueba preliminar. Estos son: 

1. El valor del material de referencia a 25 grados centigrados.
2. La temperatura actual del material de referencia.
3. Con los datos anteriores se realiza la correcciondel material de referencia por temperatura.
4. Valor indicado por el equipo evaluado.
5. El milivoltaje que indica el equipo de medicion paara la lectura de ph.
6. Con estos Datos se calcula el error.

Con los datos obtenidos se evalua si el equipo cumple con el criterio de aceptacion tomando como referencia el EMP, debe cumplir para cada repeticion. De no ser asi el equipo no esta apto para realizar su operacion asignada y se debe informar al cliente.

Se tendra un campo para describir las observaciones del proveso realizado.

Se debe seleccionar que operario realizo el proceso de calibracion.

Co la informacion recolectada se generara un reporte de calibracion que sera entregado al cliente con toods los resultados obtenidos del proceso.



![WhatsApp Image 2025-08-15 at 10 01 29 AM](https://github.com/user-attachments/assets/7ab237a6-3c20-44d4-ab22-d1dedc805dd1)![WhatsApp Image 2025-08-15 at 10 00 52 AM](https://github.com/user-attachments/assets/0b4fee38-0e04-4aab-80a4-ad7b59286b18)
