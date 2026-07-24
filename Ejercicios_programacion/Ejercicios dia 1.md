1. Imprime en consola un 'hola mundo'
2. Dado a un metodo el nombre y edad el programa debe devolver `Hola <nombre> tienes <anios> anios`
3. Realiza una funcion suma de 2 numeros dados por el usuario
4. Dado un numero, devolver si el numero es par o impar
5. Dado `base, altura` de un rectangulo, sacar el area del rectangulo


## Solucion

### Ejercicio 1

   ```code
   public void holaMundo(){
	   System.out.println("Hola mundo");
   }
   ```

### Ejercicio 2

``` code
public void saludo(String nombre, int edad){
	System.out.println("Hola" + nombre + "tienes" + edad + "anios");
}
```

### Ejercicio 3

```code
public int suma(int a, int b){
	return a+b;
}
```

### Ejercicio 4

```code
public String esPar(int num){
	if(num % 2 == 0){
		return "Es Par";
	}else{
		return "Es Impar";
	}}
```

### Ejercicio 5

```code

public int areaRectangulo(int altura, int base){
	return altura*base;
}
```
