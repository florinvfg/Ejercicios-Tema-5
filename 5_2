/*
  5.2  Diseniar un programa que solicite al usuario
que introduzca por teclado 5 numeros
decimales. A continuacion,mostrar los numeros en
el mismo orden que se han introducido
 */
package javaapplication5.pkg2;

import java.util.Arrays;
import java.util.Locale;
import java.util.Scanner;

public class JavaApplication52 {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);
        sc.useLocale(Locale.US);//para separar los decimales con punto no con coma
        double t[] = new double[5];//declaracion y creacion de la tabla con longitud 5

        for (int i = 0; i < 5; i++) { //recorremos para leer lo valores
            System.out.println("Introduzca un numero: ");
            t[i] = sc.nextDouble();
        }

        System.out.println(Arrays.toString(t)); //muestra "t"

    }

}
