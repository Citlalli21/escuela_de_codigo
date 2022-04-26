# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

* Programa que pida un número y diga si es positivo o negativo
* Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.
* 1 inicio
* 2 declarar (letra)char
* 3 mostrar "ingrese una letra para validar"
* 4 asignar (letra)
* 5 si letra== "s" o letra == "n" 
  * imprime "correcto"
  * sino
  * imprime "incorrecto"
  * finsi
* 6 finproceso
![image](https://user-images.githubusercontent.com/103066352/164306723-4ee40dcb-4521-4ff5-a5c2-7ec9a056fc3f.png)


* Un programa que pida una letra y detecte si es una vocal.
* 1 inicio
* 2 declarar (letra) char
* 3 mostrar"ingrese una letra"
* 4 asignar (letra= a, e, i, o, u)
* 5 si letra = a, e, i, o, u
* 6 imprime vocal
* 7 si no
* 8 finsi
* 9 finproceso


* Programa que pida 3 números y los muestre en pantalla de menor a mayor.  
* 1 inicio
* 2 declarar (letra) int
* 3 mostrar "ingrese un numero"
* 4 asignar (letra= a, b, c)
* 5 si (letra = a< b y letra =b<c y letra = a<c )
*   mostrar a b c
*   si no 
*   si letra = b<a y letra = b<c y letra = a<c
*   mostrar  b a c
*   si no 
 *   si letra c<a y c<b y a<c
 *   mostrar b c a
 *  si no
 *  si letra a<b y c<a a<b                        
 *  mostrar c a b
 *   si no                        
 *  si letra = a<c y a<b y c<b
 *  mostrar a c b
 * si no                           
 * si letra = c<b y b<a y c<a
 * mostrar c b a    
 * 6 fin si 
 * 7 fin proceso                            
               
    
* De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.
* 1 inicio
* 2 declarar (dia) int
* 3 mostrar (ingrese numero)                             
* 4 asignar (dia)
* 5 en caso de dia 1 mostrar "enero"
                              2 mostrar "febrero"
                              3 mostrar "marzo"
                              4 mostrar "abril"
                              5 mostrar "mayo"
                              6 mostrar "junio"
                              7 mostrar "julio" 
                              8 mostrar "agosto"
                              9 mostrar "septiembre"
                              10 mostrar "octubre"
                              11 mostrar "noviembre"
                              12 mostrar "diciembre" 
                              SINO MOSTRAR "FAVOR DE INTRODUCIR UN NUEMRO DEL 1 AL 12" 
                              
![image](https://user-images.githubusercontent.com/103066352/164533070-0042b82e-a942-4253-93d1-29d7dc1a08f0.png)


*fincaso
*fin                               
                      
* De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.
* 1 inicio
* 2 declarar (letra) int   
* 3 mostrar "vote por un candidato"
* 4 asignar (letra)
* 5 en caso de letra a mostrar "Usted ha votado por el partido rojo"
                              b mostrar "Usted ha votado por el partido verde"
                              c mostrar " usted ha votado por el partido azul"
                              SI NO MOSTRAR "opción erronea"
                              
                              
* Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.
