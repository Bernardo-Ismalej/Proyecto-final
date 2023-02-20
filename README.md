# Proyecto-final
complementar el codigo 
El valor de la cotizacion va a variar segun sea el caso de la persona, verificar 
en que rango de edad, si estuviera casado, tambien depende de la edad del conyuge
y si la persona tiene hijos, estas condiciones elevaran el precio base dependiendo
de los datos que de la persona.

El programa pedira al usuario engresar su nombre, para ello se utilizo un prompt, 
para que el usuario pueda interactuar con el programa, seguidamente la edad, en 
esta etapa se utiliza una condicional ya que la variable edad cuenta con tres 
condiciones:
1. La persona que tenga de 18 a 24 años se le aplicara un recargo del 10%
2. Si la persona tiene el rango de edad de 25 a 49 años se le aplicara un recargo del 20%
3. Y por ultimo si la persona tiene de 50 años en adelante se le aplicara el 30% de recargo 

La variable casado tendra la funcion de pedir al usuario su estado civil, si esta casado o 
no, si lo estuviere se le aplicara un recargo de acuerdo a la edad del conyuge, de lo contrario
no se le aplicara este recargo.

En la parte del programa donde indica al usuario que escriba si tiene o no hijos, si diera el 
caso que tenga se le aplicaria un recargo el 20% del precio base por cada hijo que tuviera.

El siguiente programa, lo realice de una forma ordenada en mi punto de vista, el plan base debia 
ser una constante por motivos de que los Q. 2000 no va a cambiar de valor, en las variables de 
recargos utilice la condicion if, if else, para determinar cuanto seria el recargo de acuerdo a 
las edades.

Me parecio que debia agregar bajo la variable edad las condiciones que se debian cumplir para ver 
de cuanto seria el porcentaje de recargo, de igual manera del conyuge, en caso de que estuviera 
casado y si tuviera hijos tambien se le aplicaria el recargo del 20%, para las edades utilice la 
funcion parseInt, para no tener que convertir el texto en numeros.

