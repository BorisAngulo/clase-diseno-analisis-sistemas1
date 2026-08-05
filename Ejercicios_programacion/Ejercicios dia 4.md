1. Disenar un juego de adivina el numero entre numeros del 1 al 100
	- se da como parametro el numero de intentos
	- por consola debo escribir el numero 
	- si me equivoco el programa me dira si en numero que ingrese es mayor o menor al generado automaticamente
	- si acierto, gano
	- si no cumplo el numero de intentos pierdo

###
```java
import java.util.Scanner;
public void juego(){
	Scanner sc = new Scanner();
	int numAleatorio = (int)(Math.random()*100)+1;
	boolean haGanado;
	int numeroUsuario = 0;
	while(!haGanado){
		System.out.println("Ingrese un numero");
		numeroUsuario = sc.nextInt();
		
		if(numeroUsuario == numAleatorio){
			haGanado = true;
		}else if(){
			
		}else{
			
		}
		
		
		
	}
	
	System.out.println("Ha ganado");
}
```

### solucion
```java
public void juego(int maxIntentos){
        Scanner scanner = new Scanner(System.in);

        // Genera un número aleatorio dentro del rango especificado
        int numeroSecreto = (int)(Math.random()*100) +1;
        int intentosRealizados = 0;
        boolean haGanado = false;

        System.out.println("=================================================");
        System.out.println("   ¡BIENVENIDO AL JUEGO ADIVINA EL NÚMERO!   ");
        System.out.println("=================================================");
        System.out.println("He pensado un número entre 0 y 100.");
        System.out.println("Tienes un máximo de " + maxIntentos + " intentos para adivinarlo.\n");

        // Bucle principal del juego
        while (intentosRealizados < maxIntentos && !haGanado) {
            intentosRealizados++;
            int intentosRestantes = maxIntentos - intentosRealizados;

            System.out.print("Intento [" + intentosRealizados + "/" + maxIntentos + "] - Ingresa tu número: ");

            // Validación para asegurar que se ingrese un entero válido
            while (!scanner.hasNextInt()) {
                System.out.println("⚠️ Por favor, ingresa un número entero válido.");
                System.out.print("Intento [" + intentosRealizados + "/" + maxIntentos + "] - Ingresa tu número: ");
                scanner.next(); // Limpiar entrada incorrecta
            }

            int numeroUsuario = scanner.nextInt();

            // Comprobación de la suposición del usuario
            if (numeroUsuario == numeroSecreto) {
                haGanado = true;
                System.out.println("\n🎉 ¡FELICIDADES! ¡Has adivinado el número " + numeroSecreto +
                        " en " + intentosRealizados + " intento(s)!");
            } else if (numeroUsuario < numeroSecreto) {
                System.out.println("❌ Incorrecto. El número secreto es MAYOR.");
                if (intentosRestantes > 0) {
                    System.out.println("Te quedan " + intentosRestantes + " intento(s).\n");
                }
            } else {
                System.out.println("❌ Incorrecto. El número secreto es MENOR.");
                if (intentosRestantes > 0) {
                    System.out.println("Te quedan " + intentosRestantes + " intento(s).\n");
                }
            }
        }

        // Condición si agota los intentos sin acertar
        if (!haGanado) {
            System.out.println("\n💀 ¡GAME OVER! Te has quedado sin intentos.");
            System.out.println("El número secreto era: " + numeroSecreto);
        }

        scanner.close();
    }
```





















