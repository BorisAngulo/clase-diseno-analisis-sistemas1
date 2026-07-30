1. Crea una funcion que halle el area de un poligono (triangulo, cuadrado o triangulo), como parametro se dara la base y la altura de la figura y la palabra de la figura
2. Crea un programa que invierta el orden de una cadena de texto  sin usar funciones  propias del lenguaje que lo hagan de forma automática.
	- Si le pasamos "Hola mundo" nos retornaría "odnum aloH"
3.  Crea un programa se encargue de transformar un número * decimal a binario sin utilizar funciones propias del lenguaje que lo hagan directamente.
4. Crear una funcion que devuelva si una palabra es o no es palindromo por ejemplo 
	- Oruro -> Oruro es palindroma

```java
	public int areaPoligono(int base, int altura, String figura){
        if(base<0 || altura < 0){
            return 0;
        }
        switch (figura) {
            case "cuadrado" -> {
                if (altura == base) {
                    return base * altura;
                } else {
                    return -1;
                }
            } case "triangulo" -> {
                return base * altura / 2;
            }
            case "rectangulo" -> {
                return base * altura;
            }
            default -> {
                return -1;
            }
        }
    }

    public String invertirCadena(String texto){
        String res = "";
        for(int i = texto.length() - 1; i>=0 ; i--){
            res = res + texto.charAt(i)  ;
        }
        return res;
    }

    public String binario(int num){
        String res = "";
        if (num == 0 )return "0";
        int residuo;
        while(num>0){
            residuo = num%2;
            num = num/2;
            res = residuo + res;
        }
        return res;
    }

    public boolean palindromo(String palabra){
        String palabraInvertida = invertirCadena(palabra);
        return palabra.equals(palabraInvertida);
    }
```