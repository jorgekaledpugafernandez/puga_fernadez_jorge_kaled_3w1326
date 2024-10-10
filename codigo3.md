print("puga fernandez jorge kaled")
# Definición de la función factorial que calcula el factorial de un número
def factorial(n):
    # Verifica si el número es negativo
    if n < 0:
        # Lanza un error si el número es negativo
        raise ValueError("El número debe ser positivo.")
    # Retorna 1 si n es 0, de lo contrario, calcula el factorial recursivamente
    return 1 if n == 0 else n * factorial(n - 1)

# Ejemplo de uso
# Solicita al usuario que ingrese un entero positivo
numero = int(input("Ingresa un entero positivo: "))
# Imprime el factorial del número ingresado llamando a la función factorial
print(f"El factorial de {numero} es {factorial(numero)}")


   ![image](https://github.com/user-attachments/assets/173f7fed-72b9-4207-889d-4bbd01897d5b)

