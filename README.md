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


## programas del tema 2
