def factorial(n):
    if n < 0:
        raise ValueError("El número debe ser positivo.")
    return 1 if n == 0 else n * factorial(n - 1)

# Ejemplo de uso
numero = int(input("Ingresa un entero positivo: "))
print(f"El factorial de {numero} es {factorial(numero)}")

    ![image](https://github.com/user-attachments/assets/3eea2ea2-4d6c-4518-8687-c9dcb80f1129)
