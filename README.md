# Ejercicio-Java-for
Escribe un programa que pida al usuario un número y luego use un bucle for para contar desde 1 hasta ese número.
SOLUCION:
import java.util.Scanner;
class Main {
    public static void main(String[] args) {
     
     Scanner entrada = new Scanner(System.in);   
     
     System.out.print("Introduce un numero ");
     String numeroString = entrada.nextLine();
     int numero = Integer.parseInt(numeroString);
     
     for(int i = 1; i <= numero; i++){
     
     System.out.println(i);
     }
    }
}
