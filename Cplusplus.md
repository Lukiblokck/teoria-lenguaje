
# 📘 Teoría Básica de C++

## ¿Qué es C++?

C++ es un lenguaje de programación de propósito general que extiende al lenguaje C, incorporando programación orientada a objetos. Es ideal para desarrollar sistemas operativos, videojuegos, controladores, y más.

---

## 🔹 Estructura Básica

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "¡Hola, mundo!" << endl;
    return 0;
}
```

---

## 🔹 Tipos de Datos

| Tipo     | Descripción                | Ejemplo               |
|----------|----------------------------|------------------------|
| `int`    | Números enteros            | `int edad = 14;`       |
| `float`  | Decimales de precisión simple | `float peso = 65.5;` |
| `double` | Decimales de doble precisión | `double pi = 3.1416;` |
| `char`   | Carácter único             | `char letra = 'A';`    |
| `bool`   | Booleano (true / false)    | `bool activo = true;`  |
| `string` | Cadena de texto (requiere `#include <string>`) | `string nombre = "Luki";` |

---

## 🔹 Entrada y Salida

```cpp
int edad;
cout << "Ingresa tu edad: ";
cin >> edad;
cout << "Tienes " << edad << " años." << endl;
```

---

## 🔹 Condicionales

```cpp
if (edad >= 18) {
    cout << "Eres mayor de edad." << endl;
} else {
    cout << "Eres menor de edad." << endl;
}
```

---

## 🔹 Bucles

### For

```cpp
for (int i = 0; i < 5; i++) {
    cout << "Repetición " << i << endl;
}
```

### While

```cpp
int i = 0;
while (i < 5) {
    cout << "Contador: " << i << endl;
    i++;
}
```

---

## 🔹 Funciones

```cpp
int sumar(int a, int b) {
    return a + b;
}

int main() {
    cout << sumar(3, 5); // Imprime 8
    return 0;
}
```

---

## 🔹 Arreglos (Arrays)

```cpp
int numeros[3] = {10, 20, 30};
cout << numeros[0]; // Muestra 10
```

---

## 🔹 Programación Orientada a Objetos (POO)

```cpp
#include <iostream>
using namespace std;

class Persona {
public:
    string nombre;
    int edad;

    void saludar() {
        cout << "Hola, soy " << nombre << " y tengo " << edad << " años." << endl;
    }
};

int main() {
    Persona p1;
    p1.nombre = "Luki";
    p1.edad = 14;
    p1.saludar();
    return 0;
}
```

---

## 🚀 ¡A programar en C++!
