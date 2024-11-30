# programas-python

Repositorio para subir los programas elaborados en la clase de fundamentos de programacion 
------------------------------------------------------------------------------------------
## programas del tema 1
# p1- Mostrar tu nombre
Un programa simple en Python que solicita al usuario su nombre y muestra un saludo personalizado.

📋 Descripción
Este programa es un ejemplo básico de interacción con el usuario en Python. Demuestra cómo utilizar las funciones input() y print() para capturar información desde la consola y mostrar un mensaje dinámico.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Funcionalidades
Solicita al usuario que ingrese su nombre.
Muestra un saludo personalizado utilizando el nombre ingresado.
------------------------------------------------------------------
📂 Código
# Este programa mostrará tu nombre
nombre = input("¿Cómo te llamas? ")
print("Hola,", nombre, "!")
-------------------------------
🖥️ Ejemplo de uso
¿Como te llamas? Juan
Hola, Juan!
---------------------------
# p2- P2.- Fiesta de Chorchis y Choto
Este programa utiliza operaciones lógicas en Python para determinar si se realizará una fiesta o no, basado en ciertas condiciones representadas por valores booleanos.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
📋 Descripción
El programa evalúa combinaciones de dos variables booleanas (A y B), representando condiciones para que se haga la fiesta. La lógica sigue esta regla:
La fiesta se lleva a cabo si not(A or B) es verdadero.
-------------------------------------------------------------------------------------------------------------------------------------------------------
Se presentan cuatro combinaciones posibles de los valores de A y B, y para cada combinación se evalúa si hay fiesta o no.
-------------------------------------------------------------------------------------------------------------------------
📂 Código
# P2.- Fiesta de Chorchis y Choto   

# | A | B || not(A or B) |  
# | 0 | 0 ||      1      |  
# | 0 | 1 ||      0      |  
# | 1 | 0 ||      0      |  
# | 1 | 1 ||      0      |  

print(not(False or False))  # Hay fiesta (True)  
print(not(False or True))   # No hay fiesta (False)  
print(not(True or False))   # No hay fiesta (False)  
print(not(True or True))    # No hay fiesta (False)  
-------------------------------------------------------
🛠️ Funcionalidades
Evalúa todas las combinaciones posibles de dos condiciones booleanas (A y B).
Determina si se cumple la lógica para hacer la fiesta.
------------------------------------------------------------------------------
🖥️ Ejemplo de salida
True  
False  
False  
False  
True indica que habrá fiesta.
False indica que no habrá fiesta.
---------------------------------------------------------------------------------
# p3- Comprueba el funcionamiento de la adición (concatenación)
Este programa muestra cómo funciona la concatenación de cadenas de texto en Python, combinando varias cadenas individuales en una sola.
-------------------------------------------------------------------------------------------------------------------------------------
📋 Descripción
El programa utiliza el operador + para concatenar (unir) varias cadenas de texto, generando una salida combinada. En este caso, se concatenan palabras que forman una frase completa.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Código
print("Mi" + "nombre" + "es" "Edinguer")
--------------------------------------------
🛠️ Funcionalidades
Une varias cadenas de texto utilizando el operador +.
Genera una salida combinada como una sola cadena.
----------------------------------------------------
🖥️ Ejemplo de salida
MinombreesEdinguer
Nota:
En Python, si dos cadenas están juntas sin un operador de concatenación explícito (como "es" "Edinguer"), se concatenan automáticamente. Por eso no es necesario el + entre "es" y "Edinguer".
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
# p4- Programa que calcula los impuestos de un valor e imprime
Este programa calcula el impuesto al valor agregado (IVA) de un valor ingresado por el usuario y muestra el valor con el IVA incluido.
--------------------------------------------------------------------------------------------------------------------------------------
📋 Descripción
El programa solicita al usuario que ingrese un valor numérico. Calcula el 16% de este valor (correspondiente al IVA) y lo suma al valor original para mostrar el total. Este tipo de cálculo es útil para determinar precios con impuestos incluidos.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Código
# Solicitar al usuario un valor para calcular el IVA
valor = float(input("Digite el valor para calcular el IVA: "))
--------------------------------------------------------------
# Calcular el IVA (16% del valor)
iva = valor * 0.16
-------------------------------------
# Mostrar el valor con el IVA incluido
print("El valor con IVA es: " + str(valor + iva))
--------------------------------------------------------
🛠️ Funcionalidades
Solicita un valor al usuario.
Calcula el 16% de IVA sobre el valor ingresado.
Muestra el valor total (incluyendo el IVA).
--------------------------------------------
🖥️ Ejemplo de uso
Entrada del usuario
Digite el valor para calcular el IVA: 100
Salida esperada:
El valor con IVA es: 116.0
--------------------------------------------
# p5- Práctica de comparación, Membership, slicing e indexado
Este programa explora conceptos básicos de Python, como comparación de cadenas, uso de operadores de pertenencia (membership), rebanado de cadenas (slicing) e indexado de caracteres en una cadena.
--------------------------------------------------------------------------------------------------------------------------------------------------------
📋 Descripción
Comparación:
Se realizan comparaciones entre cadenas utilizando operadores como ==, !=, <, y >.
-------------------------------------------------------------------------------------
Membership:
Utiliza los operadores in y not in para verificar si una subcadena está presente o ausente dentro de otra cadena.
--------------------------------------------------------------------
Slicing:
Se obtiene un fragmento de una cadena utilizando índices.
---------------------------------------------------------
Indexado:
Permite acceder a caracteres específicos de una cadena mediante su posición.
----------------------------------------------------------------------------
📂 Código
print("COMPARACIÓN:")  
print("Perro" == "Perro")  # True  
print("Perro" != "Gato")  # True  
print("Aguascalientes" < "Zacatecas")  # True  
print("Aire" > "Agua")  # True  
print("\nMEMBERSHIP:")  
------------------------------------------------------
# Revisa si la primera cadena está en la segunda  
print("house" in "Boathouse")  # True  
print("bien" in "bienvenidos")  # True  
print("Y" not in "ejes")  # True  
print("je" not in "ejes")  # False  
print("\nSLICING:")  
print("Sirve para obtener un fragmento de una cadena dada. Si solo deseamos obtener un solo carácter, entonces usaremos la indexación")  
---------------------------------------------------------------------------------------------------------------------------------
print("INDEXING:")  
mi_nombre = "Choto Chorchis"  
print(mi_nombre[3])  # Obtiene el cuarto carácter: "t"  
print(mi_nombre[12])  # Obtiene el último carácter: "s"  
print(mi_nombre[2:6])  # Obtiene un fragmento desde el índice 2 al 5: "oto" 
-----------------------------------------------------------------------
🛠️ Funcionalidades
Comparación de cadenas:
Compara cadenas utilizando operadores relacionales.
Membership:
Verifica si una subcadena está contenida dentro de otra (in, not in).
Slicing:
Extrae un rango de caracteres de una cadena dada.
Indexado:
Accede a un carácter específico de una cadena mediante su posición.
----------------------------------------------------------------------
🖥️ Ejemplo de salida
plaintext
Copiar código
COMPARACIÓN:  
True  
True  
True  
True  

MEMBERSHIP:  
True  
True  
True  
False  

SLICING:  
Sirve para obtener un fragmento de una cadena dada. Si solo deseamos obtener un solo carácter, entonces usaremos la indexación  
INDEXING:  
--------------------------------------------------------------------------------------

## programas del tema 2
