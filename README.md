![Tec de Monterrey](images/logotecmty.png)
# Actividad 4.3 Implementación búsqueda geométrica

## <span style="color: rgb(26, 99, 169);">¿Qué tengo que hacer?</span>
En este repositorio encontrarás el archivo "main.cpp". En este archivo deberás desarrollar la implementación del problema presentado en esta actividad. En la parte superior del archivo coloca, en comentarios, tus datos. Por ejemplo:
```
// =========================================================
// File: main.cpp
// Authors:
//  Edward Elric - A00123456
//  Alphonse Elric - A00124598
// Date: 01/01/2021
// =========================================================
```
Implementa, <span style="text-decoration-line: underline;">en equipos de 2 personas (máximo)</span>, un programa en C++ que implemente el algoritmo Randomized Binary Search Algorithm para determinar si un número entero en un conjunto de números enteros, a través del método Las Vegas Randomized Algorithm, en la siguiente referencia se puede consultar este método: [Randomized Algorithms](https://www.geeksforgeeks.org/randomized-algorithms-set-2-classification-and-applications/)

## <span style="color: rgb(26, 99, 169);">**Entrada**</span>
El programa recibe un número entero, *N*, la cantidad de números enteros a leer. En la siguiente línea, encontrarás *N* números enteros. A continuación, un número entero, *Q*, la cantidad de números a buscar. Por último, los *Q* números enteros a buscar.

## <span style="color: rgb(26, 99, 169);">**Salida**</span>
Deberá desplegar la cantidad de búsquedas realizadas usando la búsqueda binaria tradicional y la cantidad de búsquedas realizadas usando el algoritmo de búsdqueda binaria aleatorizado. En caso de que alguna búsqueda no encuentre el número, deberá regresar -1.

## <span style="color: rgb(26, 99, 169);">**Ejemplo de entrada**</span>
```
10
8 11 13 2 10 2 17 18 0 5
3
8 1 17

```

## <span style="color: rgb(26, 99, 169);">**Ejemplo de salida**</span>
```
number = 8 using binary search = 1, using randomize binary search = 2
number = 1 using binary search = -1, using randomize binary search = -1
number = 17 using binary search = 3, using randomize binary search = 4

```
**IMPORTANTE:** El número de búsquedas realizadas usando la versión aleatorizada puede variar.

Para probar tu implementación, compila tu programa con el comando:
```
g++ -std=c++11 main.cpp -o app
```
Posteriormente, ejecuta tu programa. Para realizar las pruebas, puedes usar las siguientes líneas de código.
```
./app > mysolution.txt
```

## <span style="color: rgb(26, 99, 169);">**¿Bajo qué criterios se evalúa mi evidencia?**</span>

- **80%** - Para cada una de las funcionalidades se evaluará:

    - **Excelente (80%)** - pasa correctamente todos los casos de prueba.
    - **Muy Bien (60%)** - pasa correctamente el 75% de los casos de prueba.
    - **Bien (40%)** - pasa correctamente el 50% de los casos de prueba.
    - **Insuficiente (20%)** - pasa correctamente menos del 50% de los casos de prueba.

- **10%** - El código deberá seguir los lineamientos estipulados en el estándar de codificación: <span class="instructure_file_holder link_holder">[liga_estándar_codificación](estandar.pdf)</span>
- **10%** - Se especifica (en comentarios) la complejidad computacional de cada uno de las funciones desarrolladas.

## <span style="color: rgb(26, 99, 169);">**¿Dónde la entrego?**</span>
Cuando hayas pasado todas las pruebas, recuerda publicar el código en tu repositorio (*git push*).

## <span style="color: rgb(26, 99, 169);">**Importante**</span>
Recuerda colocar el nombre y las matrículas de ambos integrantes en en los comentarios iniciales. En caso de que se incumpla este punto, se penalizará con 20 puntos sobre la calificación obtenida.
