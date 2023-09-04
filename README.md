![](../../workflows/gds/badge.svg) ![](../../workflows/docs/badge.svg) ![](../../workflows/wokwi_test/badge.svg)

# Circuito creyente

## Descripción
Un circuito BCD  display 7 segmentos que despliega caracteres para formar una palabra. 

## Funcionamiento
Son compuertas logicas que crean una funcion para desplegar caracteres en un display de 7 segmentos. Eb este caso los caracteres forman dos palabras por lo que utilizamos una entrada de seleccion para elegir cual de ambas se muestran.

## Como probarlo
En las entradas 0 a 3 escribir un numero binario con la ultima entrada (3) como el bit menos significante. Al escribirlos en orden de 0 a 9 se desplegará la palabra, la cual se selecciona con la entrada 7.





