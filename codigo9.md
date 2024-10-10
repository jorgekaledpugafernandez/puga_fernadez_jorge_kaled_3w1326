print("puga fernandez jorge kaled")
# Función para sumar todos los números de una lista
def suma(lista):
    # Retorna la suma de todos los elementos en la lista
    return sum(lista)  # Utiliza la función incorporada sum()

# Función para multiplicar todos los números de una lista
def multip(lista):
    # Inicializa el resultado en 1 (neutro para la multiplicación)
    resultado = 1
    # Itera sobre cada número en la lista
    for numero in lista:
        # Multiplica el resultado por cada número
        resultado *= numero
    # Retorna el resultado final de la multiplicación
    return resultado

# Ejemplo de uso
# Define una lista de números
numeros = [1, 2, 3, 4]

# Llama a la función suma y muestra el resultado
print(f"La suma de la lista es: {suma(numeros)}")  # Debe devolver 10

# Llama a la función multip y muestra el resultado
print(f"La multiplicación de la lista es: {multip(numeros)}")  # Debe devolver 24

![image](https://github.com/user-attachments/assets/d4f81264-e3ab-4e22-89a2-4070732ed5bf)
![image](https://github.com/user-attachments/assets/3b950df4-a7d1-4789-b4c1-df01387c36e9)


