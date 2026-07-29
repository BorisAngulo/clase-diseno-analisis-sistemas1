1. Imprime numeros segun la cantidad proveida al metodo, por ejemplo si le doy 10 debe contar 1, 2, 3, 4, ...... , 10
2. Realiza una funcion para saber si `num1` es divisible entre `num2`
3. Escribe un programa que muestre por consola (con un print) los números de 1 a 100 (ambos incluidos y con un salto de línea entre cada impresión), sustituyendo los siguientes:
   - Múltiplos de 3 por la palabra "fizz".
   - Múltiplos de 5 por la palabra "buzz".
   - Múltiplos de 3 y de 5 a la vez por la palabra "fizzbuzz".
4. Escribe un programa que imprima los 50 primeros números de la sucesión de Fibonacci empezando en 0.
- La serie Fibonacci se compone por una sucesión de números en la que el siguiente siempre es la suma de los dos anteriores.
  0, 1, 1, 2, 3, 5, 8, 13...


1. ```java
   public void contar(int num){
	   for(int i = 0; i<num; i++){
		   System.out.println(i);
	   }
   }
   ```
2. ```java
   public boolean divisible(int num1, int num2){
	   if(num1 % num2 == 0){
		   return true;
	   }else{
		   return false;
	   }
   }
   ```
3. ```java
   public void fizzbuzz(){
	   for(int i = 1; i<=100; i++){
		   if(i%3 == 0 && i%5 ==0){
			   System.out.println("buzz")
		   else if(i%3 == 0){
			   System.out.println("fizz")
		   }else if(i%5 == 0){
			   System.out.println("buzz")
		   }else{
			   System.out.println("i")
		   }
	   }
   }
   ```
4. ```java
   public int[] fibonacci(){
        int[] res = new int[50];
        for (int i = 0; i<50; i++){
            if (i == 0){
                res[i] = 0;
            }else if(i == 1){
                res[i] = 1;
            }else{
                res[i] = res[i-1] + res[i-2];
            }
        }
        return res;
    }
   ```
   Solucion sin arrays
```java
   public void fibonacci(){
        int num1 = 0;
        int num2 = 1;
        int aux = 0;
        for (int i = 0; i<50; i++){
	        if(i == 0){
		        System.out.println(num1);
	        }else if(i == 1){
		        System.out.println(num2);
	        }else{
		        
		        System.out.println(num1+num2);
		        aux = num1;
		        num1 = num2;
		        num2 = num1+num2;
	        }
        }
    }
```