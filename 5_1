/*
 * 5.1 Crea una tabla de longitud 10 que se inicializara con numeros aleatorios
comprendidos entre 1 y 100.Mostrar la suma de todos los numeros aleatorios
que se guardan en la tabla
 */
package javaapplication5.pkg1;

public class JavaApplication51 {

    public static void main(String[] args) {
        int valores[];
        valores = new int[10];

        for (int i = 0; i < valores.length; i++) {
            valores[i] = (int) (Math.random() * 100 + 1);

            int suma = 0;
            for (int valor : valores) {
                suma += valor;
            }
            System.out.println(" La suma de los valores aleatorios es" + suma);

        }
    }
}

