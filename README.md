# Diagramas-Segunda-Parcial

### Ejercicio 1 en for. Se desea obtener como salida el mensaje de "Contar del 1 hasta e 10 y sumar los valores".
#### 1.1 Análisis.
Se necesita utilizar un simbolo de proceso que haga una suma=0, despues un contador for, despues de introducir lo requerido en el ciclo ford se va a otro simbolo de proceso donde suma es igual a suma mas contador, de hay se regresa al ciclo y hasta que el ciclo se cumpla se va a un simbolo de datos donde pregunta suma y se termina.
#### 1.2 Diagrama de Flujo.
[![1.png](https://i.postimg.cc/PrFRNTtz/1.png)](https://postimg.cc/WhgnHRqh)
#### 1.3 Prueba de Escritorio.
|S=0|i=1|i<=10|S=S+1|i++|S|
|-|---|---|---|---|---|
|1|1|si|2|i++|2|
#### 1.4 Entradas 
Ninguna
#### 1.5 Salidas 
Una 
#### 1.6 Códigos
```
// Contar del 1 hasta el 10 y sumar los valores.

void main(List<String> args) {
  int s = 0;
  for (var i = 1; i <= 10; i++) {
    s += i;
  }
  print("La suma de los valores es: $s");
}//for
```

### Ejercicio 2 en do-wile. CONTAR DEL 1 HASTA EL 10 Y SUMAR LOS VALORES.
#### 2.1 Anáisis.
Se necesita un simbolo de proceso de datos donde S=0 y C=1, luego se necesita otro simbolo de proceso de datos donde S=C+S, mas tarde se pone otro simbolo de proceso donde C=C+1, despues de pone un simbolo de condicion donde te dice que c<=10, si la condicion es si se regresa al simbolo de proceso donde S=c+s, si la condicion es no se imprime S.
#### 2.2 Dagrama de Flujo.
[![2.png](https://i.postimg.cc/0jmWMJZT/2.png)](https://postimg.cc/QK8kvC2m)
#### 2.3 Prueba de Escritorio.
|S=0|C=0|S=C+S|C=C+1|C<=10|S|
|-|---|---|---|---|---|
|1|1|2|2|SI|2|
|2|2|4|3|SI|4|
#### 2.4 Entradas.
Ninguna
#### 2.5 Salidas 
Una 
#### 2.6 Códigos.
```
// Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s += c;
    c++;
  } while (c <= 10);
  print("El resultado de la suma de los valores es:$s");
}//Do whilesss
```

### Ejercicio 3 en wile. CONTAR DEL 1 HASTA EL 10 Y SUMAR LOS VALORES.
#### 3.1 Análisis.
Se necesita un simbolo de proceso donde S=0 y C=1, despues se pone un simbolo de condicion que C<=10, si la condicion es si se pone un simbolo de proceso que S=C+S, de luego se pone otro simbolo de proceso donde C=C+1, de hay se regresa al simbolo de condicion, si la condicon es no se pone un simbolo de saida.
#### 3.2 Diagrama de Flujo.
[![3.png](https://i.postimg.cc/sgG3LmjY/3.png)](https://postimg.cc/18PxnpNX)
#### 3.3 Prueba de Escritorio.
|S=0|C=1|C<=10|S=C+S|C=C+1|S|
|-|---|---|---|---|---|
|0|1|SI|1|2|1|
|1|2|SI|3|3|3|
#### 3.4 Entradas.
Ninguna
#### 3.5 Salidas.
Una que imprima S
#### 3.6 Codigo.
```
// Contar del 1 hasta el 10 y sumar los valores.
void main(List<String> args) {
  int s = 0, c = 1;

  while (c <= 10) {
    s += c;
    c++;
  }
  print("El resultado de la suma de los valores es:$s");
} //while
```

### Ejercicio 4 en for. OBTENGA LA SUMA DE LOS PRIMEROS 5 NUMEROS PARES.
#### 4.1 Análisis.
Se necesita un simolo de proceso donde S=0, despues un ciclo for donde i=2; 1<=10; i=1+2, luego otro  simbolo de proceso donde S=S+i, si el ciclo se repide se hace lo mismo, pero si el ciclo no se repite se pone un simbolo de salida de datos donde se imprime S.
#### 4.2 Diagrama de Flujo.
[![4.png](https://i.postimg.cc/8k6vW2rG/4.png)](https://postimg.cc/fkMkQgKq)
#### 4.3 Prueba de Escritorio.
|S=0|i=2|i<=10|i=i+2|S=S+i|S|
|-|---|---|---|---|---|
|0|2|SI|4|2|2|
|2|4|SI|6|6|6|
#### 4.4 Entradas.
Nunguna
#### 4.5 Salidas.
Una que imprime S
#### 4.6 Codigo

```
void main(List<String> args) {
  int s = 0;
  for (var i = 2; i <= 10; i = i + 2) {
    s = s + i;
  }
  print("resultado de la suma de numeros pares es:$s");
} //For
```

### Ejercicio 5 en do-wile. OBTENGA LA SUMA DE LOS PRIMEROS 5 NUMEROS PARES.
#### 5.1 Análisis. 
Se inicia con simbolo de proceso donde S=0 C=1, luego se usa otro simbolo de proceso donde S=S+C*2, de hay se utiliza de nuevo el simbolo de proceso que C=C+1, de hay se utiliza un simbolo de condicion que C<=5, si la condicion es si se regresa al simbolo de proceso que S=S+C*2, si la condicion es no se usa el simbolo de salida de datos para imprimir S.
#### 5.2 Diagrama de Flujo
[![5.png](https://i.postimg.cc/JzZDHZyQ/5.png)](https://postimg.cc/sMfDtB4B)
#### 5.3 Prueba de Escritorio.
|S=0|C=1|S=S+C*2|C<=5|S|
|-|---|---|---|---|
|0|1|2|SI|2|
|2|1|6|SI|6|
|6|1|14|SI|14|
|14|1|30|SI|30|
|30|1|62|SI|62|
#### 5.4 Entradas.
Ninguna
#### 5.5 Salidas.
una donde se imprime S
#### 5.6 Código.
```
void main(List<String> args) {
  int s = 0, c = 1;
  while (c <= 5) {
    s = s + c * 2;
    c = c + 1;
  }
  print("resultado de la suma de numeros pares:$s");
} //While
```

### Ejercicio 6 wile. OBTENGA LA SUMA DE LOS PRIMEROS 5 NUMEROS PARES.
#### Análisis.
Se inicia con un simbolo de proceso donde S=0 y C=1, de ahi se usa un simbolo de condicion donde C<=5, si la condicion es si se pone un simbolo de proceso que dice que S=S+C*2 se pone otro simbolo de proceso que C=C+1, de ahi se regresa a la condicion de nuevo, si la condicion es no se pone un simbolo de proceso donde se imprime S.
#### Diagrama de Flujo.
[![6.png](https://i.postimg.cc/13wBRgsk/6.png)](https://postimg.cc/G43GqmBK)
#### Prueba de Escritorio.
|S=0|C=1|C<=5|S=S+C*2|C=C+1|S|
|-|---|---|---|---|---|
|0|1|SI|2|2|2|
|2|2|SI|8|3|8|
|8|3|SI|22|4|22|
|22|4|SI|52|5|52|
|52|5|SI|114|6|114|
#### 6.4 Entradas.
Ninguna.
#### 6.5 Salidas.
Una donde se imprime S
#### 6.6 Código.

```
void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s = s + c * 2;
    c = c + 1;
  } while (c <= 5);
  print("la suma de numeros pares es:$s");
} //Do While
```

### Ejercicio 7 en for. ALMACENE EN UN ARRAY EL NUMERO N LEIDO DEL TECLADO EL TAMAÑO DEL ARRAY ES 10. 
#### 7.1 Análisis.
Se inicia con un simbolo de proceso donde A[10], de hay se introduce un simbolo de entrada N, despues se utiliza el ciclo for que i=0; i<=9; i++, si el ciclo se repite se utiliza un simbolo de proceso donde A[i]=N, si el ciclo no se repite se utiliza el simbolo de salida donde se imprime A.
#### 7.2 Diagrama de Flujo.
[![7.png](https://i.postimg.cc/8C235865/7.png)](https://postimg.cc/LqVvCbvK)
#### 7.3 Prueba de Escritorio.
|A[10]|N|i=0|i<=9|i++|A|
|-|---|---|---|---|---|
|1|3|0|SI|3|2|
|2|4|3|SI|5|4|
#### 7.4 Entrada.
Una donde se busca N
#### 7.5 Salida. 
Una donde se imprime A
#### 7.6 Código.
```
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
  }
  stdout.write("aqui esta la lista, $arra");
}
```

### Ejercicio 8 do-wile. ALMACENE EN UN ARRAY EL NUMERO N LEIDO DEL TECLADO EL TAMAÑO DEL ARRAY ES 10. 
#### 8.1 Análisis.
Se inicia con un simbolo de proceso que A[10], de ahi se usa un simbolo de entrada N, despues se usa un simbolo de proceso que C=0, despues de eso se vuelve a usar otro simbolo de proceso que dice que A[C]=N, de ahi otro simbolo de proceso que C=C+1, despues se usa un simmbolo de condicion que C<=9, si la codicion es si se regresa al simbolo de proceso de A[C]=N, si la condicion es no se usa un simbolo de salida de datos y se imprime A.
#### 8.2 Diagrama de Flujo.
[![8.png](https://i.postimg.cc/P5SJBjRB/8.png)](https://postimg.cc/qNCp390L)
#### Prueba de Escritorio.
|A[10]|N|C=0|A[C]=N|C=C+1|C<=9|A|
|-|---|---|---|---|---|---|
|10|4|0|0|1|SI|10|
|10|5|1|10|2|SI|10|
#### 8.4 Entradas.
Una N
#### 8.5 Salidas.
Una donde se Imprime A
#### 8.6 Códigos.
```
import 'dart:io';

void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
  } while (i <= 9);
  stdout.write("Tu lista es $arra ");
}
```

### Ejercicio 9 wile. ALMACENE EN UN ARRAY EL NUMERO N LEIDO DEL TECLADO EL TAMAÑO DEL ARRAY ES 10. 
#### 9.1 Análisis.
Se usa un simbolo de proceso que A[10], de ahi se usa un simbolo de enrtada de datos que N, despues un simbolo de proceso que C=0, luego un simbolo de condicion que C<=9, si la condicion es si se va aun simbolo de proceso que A[C]=N, luego a otro simbolo de proceso que C=C+1, de hay se regresa al simbolo de condicion, despues si la condicion es no se sale un simbolo de salida de datos que imprime A.
#### 9.2 Diagrama de Flujo.
[![9.png](https://i.postimg.cc/CLLsDFk2/9.png)](https://postimg.cc/hh6mRRC8)
#### 9.3 Prueba de Escritorio.
|A[10]|N|C=0|C<=9|A[C]=N|C=C+1|A|
|-|---|---|---|---|---|---|
|10|3|0|SI|0|1|10|
|10|2|1|SI|10|2|10|
#### 9.4 Entradas.
Una donde se entra N
#### 9.5 Salida
Una que se usa una salida de datos que se imprime A.
#### 9.6 Códigos.
```
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
}
```


### Ejercicio 10 for. ALMACENE LOS N NUMEROS LEIDOS DEL TECLADO EN UN VECTOR DE 10 ELEMENTOS.
#### 10.1 Análisis.
Se inicia con un simbolo de proceso de datos A[10], de hay se introduce un simbolo de entrada de datos N, de hay se utiliza el ciclo for donde i=0; i<=9; i++, luego se pone un simbolo de proceso que A[i]=N, de hay se utiliza un simbolo de salida de datos que se imprime A.
#### 10.2 Diagrama de Flujo.
[![10.png](https://i.postimg.cc/4ybsVDHf/10.png)](https://postimg.cc/Wq3BPf7C)
#### 10.3 Prueba de Escritrio.
|A[10]|N|i=0|i<=9|i++|A[i]=N|A|
|-|---|---|---|---|---|---|
|10|4|0|SI||0|10|
|10|3|0|SI|1|10|
#### 10.4 Entradas.
Una donde se pone N
#### 10.5 Salidas.
Una donde se pone un simbolo de salida de datos que imprime A
#### 10.6 Códigos


### Ejercicio 11 do-wile. ALMACENE LOS N NUMEROS LEIDOS DEL TECLADO EN UN VECTOR DE 10 ELEMENTOS.
#### 11.1 Análisis. 
Se empieza con un simbolo de proceso donde A[10], de ahi se utiliza otro simbolo de proceso que C=0, luego se introduce el simbolo de entrada que es N, por lo que continua con el simbolo de proceso que dice A[C]=N, de ahi se vuelve a introducir otro simbolo de proceso de C=C+1, lo que lleva a meter un simbolo de condicion que dice C<=9, si la condicion dice si se regresa al simbolo de proceso de A[C]=N, si la condicion es no se pide un simbolo de salida de datos para imprimir A.
#### 11.2 Diagrama de Flujo.
[![11.png](https://i.postimg.cc/SRK9JbK9/11.png)](https://postimg.cc/zb9vcMKD)A
#### 11.3 Prueba de Escritorio.
|A[10]|C=0|N|A[C]=N|C=C+1|C<=9|A|
|-|---|---|---|---|---|---|
|10|0|3|0|1|SI|10|
|10|1|4|10|2|SI|10|
|10|2|2|20|3|SI|20|
#### 11.4 Entrada.
Sola una que es N
#### 11.5 Salida 
Solo una que es un simbolo de salida que imprime A
#### 11.6 Códigos.


### Ejercicio 12 wile. ALMACENE LOS N NUMEROS LEIDOS DEL TECLADO EN UN VECTOR DE 10 ELEMENTOS.
#### 12.1 Análisis.
Se inicia con un simbolo de proceso de datos que A[10], se pone otro simbolo de datos que C=0, de ahi se pone una condicion C<=9, si la condicion es si se mete un simbolo de entrada N, despues un simbolo de proceso que A[C]=N, luego se vuelve a introducir otro simbolo de proceso que C=C+1, de hay se regresa hasta la condicion, si la condcion es no se ocupa un simbolo de salida de datos donde se imprima A.
#### 12.2 Diagrama de Flujo.
[![12.png](https://i.postimg.cc/nrSMwdJf/12.png)](https://postimg.cc/RJfMWLhg)
#### 12.3 Prueba de Escritorio.
|A[10]|C=0|C<=9|N|A[C]=N|C=C+1|A|
|-|---|---|---|---|---|---|
|10|0|SI|2|0|1|10|
|10|1|SI|3|10|2|10|
#### 12.4 Entrdas.
Solo se ocupo una "N"
#### 12.5 Salida.
Se ocupo una salida de datos para imprimir A.
#### 12.6 Códigos.

### Ejercicio 13 For. ALMACENE UN CONTADOR NEGATIVO EN UN VECTOR, EL CONTEO ES DE 10 A 0.
#### 13.1 Análisis.
Se inicia con un simbolo de proceso de A[11), despues con el ciclo for donde i=10; i>=0; i=i-1, si el ciclo se repite se va a un simbolo de proceso que A[10-1]=i, si el ciclo no se repite se usa un sibolo de salida de datos que imprima A.
#### 13.2 Diagrama de flujo.
[![13.png](https://i.postimg.cc/mZ314gVn/13.png)](https://postimg.cc/pyTLYxwQ)
#### 13.3 Prueba de Escritorio.
|A[11]|i=10|i>=0|i=i-1|A[10-i]=i|A|
|-|---|---|---|---|---|
|11|10|SI|9|1|11|
|11|1|SI|0|10|11|
#### 13.4 Entradas.
Ninguna.
#### 13.5 Salidas.
Una donde se usa un simbolo de salida de datos para imprimir A
#### 13.6  Codigos
```
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.

void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  for (var i = 10; i >= 0; i--) {
    arr[10 - i] = i;
  }
  print(arr);
}
```

### Ejercicio 14 do-wile. ALMACENE UN CONTADOR NEGATIVO EN UN VECTOR, EL CONTEO ES DE 10 A 0.
#### 14.1 Análisis. 
Se inicia con un simbolo de proceso que A[11], luego se nececito otro sibolo de proceso que C=10, se vuelve a utilizar otro simbolo de proceso en donde A[10-]=A, de ahi se pone otro simbolo de proceso que C=C-1, despues te pide una condicion que C>=0, si la condicion es si se regresa al simbolo de proceso que A[10-C]=A, si la condicion es no se utiliza un simbolo de salida de dato que imprima A.
#### 14.2 Diagrama de Flujo.
[![14.png](https://i.postimg.cc/VkwR1kxZ/14.png)](https://postimg.cc/SJZ8fkNc)
#### 14.3 Prueba de Escritorio.
|A[11]|C=10|A[10-C]=A|C=C-1|C>=0|A|
|-|---|---|---|---|---|
|11|10|1|9|SI|10|
|11|9|1|8|SI|9|
#### 14.4 Entradas 
Ninguna
#### 14.5 Salidas 
Una salida de datos donde se imprime A
#### 14.6 Código.
```
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  do {
    arr[10 - c] = c;
    c = c - 1;
  } while (c >= 0);
  print(arr);
}//dowhile
```

### Ejercicio 15 wile. ALMACENE UN CONTADOR NEGATIVO EN UN VECTOR, EL CONTEO ES DE 10 A 0.
#### 15.1 Análisis.
Se inicia con un simbolo de proceso que A[11], de ahy otro simbolo de proceso que C=10, luego se usa una condicion que C>=0, si l condicion es si se pone un simbolo de proeso que A[10-C]=A, de ahi se pone otro simbolo de proceso que C=C-1, y se regresa a la condicion, si la condicion es no se unsa un simbolo de salida de datos que se imprime A.
#### 15.2 Diagrama de Flujo.
[![15.png](https://i.postimg.cc/yYf8qc1Y/15.png)](https://postimg.cc/jL7bPWnG)
#### 15.3 Prueba de Escritorio.
|A[11]|C=10|C>=0|A[10-C]=A|C=C-1|A|
|-|---|---|---|---|---|
|11|10|SI|0|9|0|
|11|9|SI|1|8|1|
#### 15.4 Entradas.
Ninguna 
#### 15.5 Salidas.
Solo una donde se usa un simbolo de salida de datos para imprimir A
#### 15.6 Coódigo.
```
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  while (c >= 0) {
    arr[10 - c] = c;
    c = c - 1;
  }
  print(arr);
}
```

### Ejercicio 16 For.   ALMACENE EN UN VECTOR DE TAMAÑO 10, TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.
#### 16.1 Análisis.
Se inicia con un simbolo de proceso que A[10], de ahi se va a un ciclo for donde i=0; i<=9; i=i+1, de ahi se utilisa un simbolo de entraa donde se pone N, luego una condicion que n%2=0, si la condicion es si se utiliza un simbolo de proceso que A[i]=N y se regresa al ciclo for y vaja de nuevo a la condicion, si la condicion es no se utiliza un simbolo de salida de datos que te dice que "TIENE QUE SER PAR", de hay te regresa al simbolo de entrada de datos hasta que pongas un numero par, cuando el ciclo for se acomplete se utiiza un simbolo de salidad de datos que imprima A.
#### 16.2 Diagrama de Flujo.
[![16.png](https://i.postimg.cc/vmns4jtc/16.png)](https://postimg.cc/VSzTTKT8)
#### 16.3 Prueba de Escritorio.
|A[10]|i=0|i<=9|i=i+1|N|N%2=0|A[i]=N|Tiene que ser par|A|
|-|---|---|---|---|---|---|---|---|
|10|0|SI|1|4|2|1||1|
|10|1|SI|2|6|3|2|NO|2|
#### 16.4 Entradas.
Una donde se pone una entradad e datos que N
#### 16.5 Salidas 
Una donde se usa una salida de datos que imprime A
#### 16.6 Codigos
```
listanumeros = []
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
numerousuario = int(input("introdusca otro numero: "))
listanumeros.append(numerousuario)

print(f"los numeros son {listanumeros}")

def pares(listanumeros):
    listanumeros = []


for n in listanumeros:
    if n % 2 == 0:
        print("Estos numeros son pares"+ "  " + str(n))
```
        

### Ejercicio 17 do-wile. ALMACENE EN UN VECTOR DE TAMAÑO 10,TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.
#### 17.1 Análisis. 
Se inicia con un simbolo de proceso donde A[10], despues otro simbolo de proceso que C=0, luego otro simbolo de proceso que C=C+1, mas tarde se usa una condicion que C<=9, si la condicion es si se introduce un simbolo de enntrada que N, depues otra condicion que N%2=0, si la condicion es si se utiliza un simbolo de proceso donde A[C]=N, si la condicion es no se utiliza un simbolo de proceso que imprima "TIENE QUE SER PAR", por lo tanto se regresa a la introduccion de un simbolo de proceso de N
si la condicion es si se regresa al simbolo de proceso donde C=C+1, si esa condicion es no la de C<=9, se utiliza un simbolo de proceso que se imprima A.
#### 17.2 Diagrama de Flujo.
[![17.png](https://i.postimg.cc/dtzTf59w/17.png)](https://postimg.cc/3dFR4C6c)
#### 17.3 Prueba de Escritorio.
|A[10]|C=0|C=C+1|C<=9|N|N%2=0|"TIENE QUE SER PAR"|A[C]=N|A|
|-|---|---|---|---|---|---|---|---|
|10|0|1|SI|4|2||1|1|
|10|1|2|SI|6|3|NO|2|2|
#### 17.4 Entradas.
Una N
#### 17.5 Salidas.
Dos "tiene que se par" y "A".
#### 17.6 Codigos.
```
print("PARES")
numero_1 = int(input("Escriba un número entero: "))
numero_2 = int(input(f"Escriba un número entero mayor o igual que {numero_1}: "))

if numero_2 < numero_1:
        print(f"¡Le he pedido un número entero mayor o igual que {numero_1}!")
else:
        for i in range(numero_1, numero_2 + 1):
            if i % 2 == 0:
                print(f"El número {i} es par.")
```

### Ejercicio 18 wile. ALMACENE EN UN VECTOR DE TAMAÑO 10, TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.
#### 18.1 Análisis.
Se inicia con un simbolo de proceso que A[10], luego otro simbolo de proceso que C=0, despues uns condicion que C<=9, si la condicion es si se utiliza un simbolo de proceso que C=C+1, se introduce una entrada de datos que N, se usa otra condicion que N%2=0, si la condicion es no te dice en un simbolo de salida que "Tiene que ser par", y se regresa a dame n que sea par, si la condicion es si se pone un simbolo de proceso que A[C]=N, se regresa a la condicion que C<=9, si esa condicion es no se utiliza un simbolo de salidad de datos que imprima A.
#### 18.2 Diagrama de Flujo.
[![18.png](https://i.postimg.cc/Z5XSNKdx/18.png)](https://postimg.cc/gxyQFp4x)
#### 18.3 Prueba de Escritorio.
|A[10]|C=0|C<=9|C=C+1|N|N%2=0|TIENE QUE SER PAR|A[C]=N|A|
|-|---|---|---|---|---|---|---|---|
|10|0|SI|1|8|4|1||10|
|10|1|SI|2|6||2||9|
#### 18.4 Entradas.
Una N
#### 18.5 Salidas. 
Dos una de "Tiene que se par" y la otra para imprimir A.
#### 18.6 Códigos. 
```
listanumeros = []
numerousuario = int(input("introdusca un numero: "))
listanumeros.append(numerousuario)
decision = input("¿desea añadadir mas numeros?: ")

while decision == "s" or decision == "s":
    numerousuario = int(input("introdusca otro numero: "))
    listanumeros.append(numerousuario)
    decision = input("¿desea añadir otro numero?: ")


print(f"los numeros son {listanumeros}")
for n in listanumeros:
    if n % 2 == 0:
        print("Este numero de la lista es par" + str(n))
        


input("por favor, precione una tecla para salir.")
```

### Ejercicio 19 for. OBTEN EL PROMEDIO DE LAS CALIFICACIONES APROBATORIAS Y LA CANTIDAD DE ALUMNOS REPROBADOS. LA CALIFICACIÓN ENTRE 0 Y 10 Y EL MAXIMO DE ALUMNOS ES DE 15.
#### 19.1 Análisis.
Se inicia con un simbolo de proceso que A[15], luego se continua con un ciclo for de i=0; i<15; i=i+1, luego se incerta un simbolo de entrada donde te pide que incertes "Alumnos", luego se inserta una condicion que Alumno_Cal>=6, si la condicion es no se pone un simbolo de salida de datos donde imprime "Reprobado", luego se regresa a la entrada de datos, si la condicion es si A[i]=APROBADO, y luego se regresa al ciclo for, si el ciclo for ya no se repite se inserta una salida de datos donde imprime A.
#### 19.2 Diagrama de Flujo.
[![19.png](https://i.postimg.cc/jSHzTr3v/19.png)](https://postimg.cc/fVb371N0)
#### 19.3 Prueba de Escritorio.
|A[15]|i=0|1<15|i=i+1|ALUMNO|ALUMNO_CAL>=6|Reprobado|A[i]=Aprobado|A|
|-|---|---|---|---|---|---|---|---|
|15|0|SI|1|1|7||Aprobado|1|
|15|0|SI|1|4|3|Reprobado||2|
#### 19.4 Entradas.
Uno "Alumnos"
#### 19.5 Salidas
Dos, uno para imprimir "Reprobado" y el otro "A".
#### 19.6. Codigos
```
alumnos = list(range(15))
p_aprobados = 0
j = 0
for i in alumnos: 
    while(True):
        calificacion = int(input("Ingresa la calificación >>"))
        if (calificacion >= 0 and calificacion <= 10):
            break
        else:
            print("Calificación fuera de rango. Intenta de nuevo")
 
    if (calificacion < 6):
     alumnos[i] = "R"
    else:
     p_aprobados = calificacion + p_aprobados
     j = j + 1
     alumnos[i] = "A"

print("\033[33;1m",alumnos,"\033[39m")
print("El promedio de calificación de los aprobados es de >>",round(p_aprobados/j,2))
print("El total de aprobados fueron >> ",j)
print("El total de reprobados fueron >> ",(len(alumnos)-j))
```

### Ejercicio 20 do-wile. OBTEN EL PROMEDIO DE LAS CALIFICACIONES APROBATORIAS Y LA CANTIDAD DE ALUMNOS REPROBADOS. LA CALIFICACIÓN ENTRE 0 Y 10 Y EL MAXIMO DE ALUMNOS ES DE 15.
#### 20.1 Análisis.
Se inicia con un simbolo de proceso que A[15], luego se utiliza otro simbolo de proceso de C=0, otro simbolo de proceso C=C+1, despues una condicion que C<15, si la condicion es si se imprime una entrada de datos que Alumnos, depues otra condcion que Alumnos_Cal>=6, si la condidon es no te pone una salida de datos que "Reprobado"y se regrasa hasta dodne te ponga aprobado, si la condicion es si te dice en un simbolo de prceso que A[C]=aPROBADO, y se regresa hasta en simbolo de proceso que C=C+1, si la condicion es no imprime en un simbolo de proceso que iprime A.
#### 20.2 Diagrama de Flujo.
[![20.png](https://i.postimg.cc/Twb9nf6s/20.png)](https://postimg.cc/0M8DsgrG)
#### 20.3 Prueba de Escritorio.
|A[15]|C=0|C=C+1|C<15|ALUMNO|ALUMNO_CAL>=6|REPROBADO|A[C]=APROBADO|A|
|-|---|---|---|---|---|---|---|---|
|15|0|1|SI|6|SI||APROBADO|7|
|15|0|1|SI|4|NO|REPROBADO||4|
#### 20.4 Entrada.
Una donde s entra Alumnos
#### 20.5 Salidas
Dos, uno donde imprime "Reprobados", y otro donde imprime A.
#### 20.6 Codigos.
```
void mydowhile(int n) {
  //siendo esta la funcion
  if (n >= 6) {
    do {
      print("pasaste con ${n}");
      n = 0;
    } while (n >= 10);
  } else {
    print("suerte para la proxima");
  }
}
```

### Ejercicico 21 wile. OBTEN EL PROMEDIO DE LAS CALIFICACIONES APROBATORIAS Y LA CANTIDAD DE ALUMNOS REPROBADOS. LA CALIFICACIÓN ENTRE 0 Y 10 Y EL MAXIMO DE ALUMNOS ES DE 15.
#### 21.1 Análisis.
Se empieza con un simbolo de proceso de A[15], otro simbolo de proceso C=0, te pide una condicion que C<15, si la condicion es si se usa C=C+1, de hay un simbolo de proceso que te dice Alumnos, de hay se introduce otra condcion que Alunos_Cal>=6, si la condicion es no te imprime una salida de datos donde te dice que "Reprobado" y se regresa a alumno, i la ondicion es si te dice A[C]=Aprobado y se regresa a la condicion C<15, si esa condicion es no se imprime una salida de datos que te imprime A.
#### 21.2 Diagrama de Flujo.
[![21.png](https://i.postimg.cc/jCYS3VLC/21.png)](https://postimg.cc/RJGmqD1z)
#### 21.3 Prueba de Escritorio.
|A[15]|C=0|C<15|C=C+1|ALUMNO|ALUMNO_CAL>=6|REPROBADO|A[C]=APROBADO|A|
|-|---|---|---|---|---|---|---|---|
|1|0|SI|1|6|SI||APROBADO|6|
|2|2|SI|3|5|NO|REPROBADO||5|
#### 21.4 Entrada.
Una donde se entra Alumnos.
#### 21.5 Salidas
Dos, una para imprimir "Reprobad" y otra para imprimir "A".
#### 21.6 Códigos.
```
alumnos = list(range(15))
p_aprobados = 0
j = 0

for i in alumnos: 
    while(True):
        calificacion = int(input("Ingresa la calificación >>"))
        if (calificacion >= 0 and calificacion <= 10):
            break
        else:
            print("Calificación fuera de rango. Intenta de nuevo")
 
    if (calificacion < 6):
     alumnos[i] = "R"
    else:
     p_aprobados = calificacion + p_aprobados
     j = j + 1
     alumnos[i] = "A"

print("\033[33;1m",alumnos,"\033[39m")
print("El promedio de calificación de los aprobados es de >>",round(p_aprobados/j,2))
print("El total de aprobados fueron >> ",j)
print("El total de reprobados fueron >> ",(len(alumnos)-j))
```

### Ejercicio 22 for. CAPTURE N NUMEROS EN EL RANGO [LI,LS] DEONDE: LI= LIMITE INFERIOR Y LS= LIMITE SUPERIOR, PARA LS<LS Y LI>0. OBTENGA: 
*CANTIDAD DE NUMEOS PARES Y SU PROMEDIO.
*CANTIDAD DE NUMEROS IMPARES Y SU PROMEDIO.
*¿QUE PROMEDIO ES MAYOR?
#### 22.1 Análisis.
Se necesita utilizar un simbolo de proceso para ingresar SO=0, CP=0, PP=0, SI=0, CI=0,PI=0, de hay se ingresa una salida de datos que te pide el "Limite inferior", luego una entrada de datos que LI, de ahi una condicion que LI>0, si la condicion es no te regresa a la salidad de datos del "límite inferior", si la condicion es si te dise una salida de datos el "Limite superior" se ingresa una entrada de datos que LS, luego otra condicion que LS>LI, si la condicion es no te imprime una salida de datos que "Tiene que ser mayor" y te regresa al limite superior,  si la condicion es si te imprime una salida de datos que "¿Cuantos numeros?", despues una entrada de datos que N, de ahi otra condicion que N>0, si la condicion es no te imprime una salida de datos que "Tiene que ser mayor" y te regresa a "Cuantos numeros", si la condicion es si se incresa un ciclo for que i=0; i<=N; i++, si el ciclo se repite te pone una salida de datos que "Dame un numero de LI y LS", de ahi se ingresa una entrada de datos que Num, de ahi una condicion que NUM>=LI AND NUM<=LS, si la condicion es no te imprime una saliada de datos que "Tiee que estar dentro de LI-LS", y te regresa a "Dame u num de LI y LS", si la condicion es si te pide otra condicon que NUM%2=0, si la condicion es no un simbolo de proceso te pide que SI=SI+NUM, y otro simbolo de proceso que CI=CI+1, y te manda al ciclo for, si la condicion es si te inrgesa un sibolo de proceso que SP=SP+NUM, de ahi otro proceso que CP=CP+1, y te manda al ciclo for, si el ciclo for ya no se repite, te pde un simbolo de proceso que CP,CI, otro simbolo de proceso que PP=SP/CP  PI=SI/CI, de ahy una entraada de datos que PP, PI, despues una condicion que PP>PI, si la condicion es si se imprime ua salida de datos que "El PP es mayor que PI" y se terina, si la condicion es no se imprime una salida de datos que "EL PI es mayor que el PP" y se imprime.
#### 22.2 Diagrama de flujo.
[![22.png](https://i.postimg.cc/tRntXV3t/22.png)](https://postimg.cc/xqYb58Fc)
#### 22.3 Prueba de Escritorio.
|SP |CP |PP |SI |CI |PI |LI |LI>0|LS |LS>LI|N  |N>0|i=1|i<=N|NUM|NUM>=LI, NUM<=LS|NUM%2=0|SP=SP+NUM|CP=CP+1|SI=SI+NUM|CI=CI+1|i++|PP=SP/CP|PI=SI/CI|PP>PI|
|---|---|---|---|---|---|---|----|---|-----|---|---|---|----|---|----------------|-------|---------|-------|---------|-------|---|--------|--------|-----|
|0  |0  |0  |0  |0  |0  |5  |SI  |99 |SI   |4  |SI |1  |1<=4|6  |6>=5, 6<=99     |SI     |6        |1      |0        |0      |2  |        |        |     |
|6  |1  |0  |0  |0  |   |   |    |   |     |   |   |2  |2<=4|87 |87>=5, 87<=99   |NO     |6        |1      |87       |1      |3  |        |        |     |
|6  |1  |0  |87 |1  |0  |   |    |   |     |   |   |3  |3<=4|98 |98>=5, 98<=99   |SI     |104      |2      |87       |1      |4  |        |        |     |
|104|2  |0  |87 |1  |0  |   |    |   |     |   |   |4  |4<=4|77 |77>=5, 77<=99   |NO     |104      |2      |164      |2      |4  |104/2   |164/2   |52>81|
#### 22.4 Entradas 
  Nunguna
#### 22.5 Salidas 
"LIMITE INFERIOR"
"LIMITE SUPERIOR"
"EL PP ES MAYOR A PI"
#### 22.6 Códigos.
```py
sp=0
cp=0
pp=0
si=0
ci=0
pi=0
li=-1
ls=-1
n=-1
num=-1
while(li<0):
    li = int(input("Limite inferior: "))
    
    if(li<0):
        print("Tiene que ser mayor a 0")
        
while(ls<li):
    ls = int(input("Limite superior: "))
    
    if(ls<li):
        print("Tiene que ser mayor que el limite inferior")
        
while(n<0):
    n = int(input("¿Cuantos numeros? "))
    
    if(n<0):
        print("Tiene que ser mayor a 0")
    
for i in range(n): 
    while(num<=li or num>=ls):
        num = int(input("Dame un numero de LI y LS: "))
        
        if(num<=li or num>=ls):
            print("Tiene que estar dentro del LI al LS")
    if(num%2==0):
        sp=sp+num
        cp=cp+1
    else:
        si=si+num
        ci=ci+1
        
    num=-1       
         
if(sp==0 or cp==0):
    pp=0
else:
    pp=sp/cp
    
if(si==0 or ci==0):
    pi=0
else:
    pi=si/ci
    
if(pp>pi):
    print("El PP es mayor que el PI")
else:
    print("El PI es mayor que el PP")
```
  
### Ejercicio 23 OBTEN LA FRECUENCIA DE N CALIFICACIONES ENTRE [1,10], INDIQUE LA CANTIDAD DE REPROBADOS Y LA CANTIDAD DE APROBADOS, EL PROMEDIO DE APROBADOS Y PROMEDIO GENERAL.
#### 23.1 Análisis.
Usar el símbolo de proceso para asignar un array para las calificaciones, pedir al usuario que ingrese las calificaciones, validar que estas esten entre 0 y 10, además de verificar en cada calificación ingressada si es mayor-igual a 6 para ingresar a las calificaciones aprobatorias, de lo contrario almacenar en las calificaciones reprobatorias, hacer las operacines correspondientes para obtener los promedios de las calificaciones aprobatorias y general , imprimir todo para finalizar.
#### 22.2 Diagrama de Flujo.
[![23.png](https://i.postimg.cc/kGq2NMcj/23.png)](https://postimg.cc/xJpjn2BH)
#### 22.3 Prueba de Escritorio.
|CAL[1,10]|N  |N>0 |i  |i<=N|CAL[1,10]|C  |C>0, C<=10|CAL[C]++|i++|CAL|
|---------|---|----|---|----|---------|---|----------|--------|---|---|
|9        |4  |4>0 |0  |0<=4| 0        |9  |9>0, 9<=0 |10      |1  |9  |
|9        |   |    |1  |1<=4|1         |9  |9>0, 9<=0 |10      |2  |9  |
|8        |4  |4>0 |0  |2<=4| 2        |8  |8>0, 8<=0 |9       |3  |8  |
|7        |   |    |1  |3<=4|  3       |7  |7>0, 7<=0 |8       |4  |7  |

|CR |CA |PR |PA |PG |SR |SA |N  |i  |i<=n|NUM|NUM>0,NUM<=10|NUM>=6|CA+1|SA+NUM|CR+1|SR+NUM|i++|PA=SA/CA|PR=SR/CR|PG=(PR+PA)/2|PG |
|---|---|---|---|---|---|---|---|---|----|---|-------------|------|----|------|----|------|---|--------|--------|------------|---|
|0  |0  |0  |0  |0  |0  |0  |4  |0  |0< 4|8  |8>=0,8<=10   |8>=6  |1   |8     |0   |0     |1  |
|0  |1  |0  |0  |0  |0  |8  |4  |1  |1< 4|5  |5>=0,5<=10   |5>=6  |1   |8     |1   |5     |2  |
|1  |1  |0  |0  |0  |5  |8  |4  |2  |2< 4|9  |9>=0,9<=10   |9>=6  |2   |17    |1   |5     |3  |
|1  |2  |0  |0  |0  |5  |7  |4  |3  |3< 4|3  |3>=0,3<=10   |3>=6  |2   |17    |2   |8     |4  |17/2    |8/4     |(8.5+4)/2   |6.25|

#### 23.4 Entradas.
"N"
"C"
"NUM"
#### 23.5 Salidas.
"¿Cuantas calificaciones?"
"¿Tiene que ser myor a 0?"
"¿Tiene que estar entre 1-10?"
"¿Cal?"
"¿Dame un numero entre el 1 y 10?"
#### 23.6 Codigos.
```py
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0
for i in range(1,Calificaciones+1):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
promedio=n/len(vec)
npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1
aprobado=0
#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h
#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado
reprobado=0
for k in vec:
    if k<5:
        reprobado=reprobado+1
print("Max Calificacion", max(vec))
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```
