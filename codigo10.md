print("puga fernnadez jorge kaled")
# Función para verificar si un carácter es una vocal
def es_vocal(caracter):
    # Define las vocales (mayúsculas y minúsculas)
    vocales = 'aeiouAEIOU'
    # Retorna True si el carácter está en la cadena de vocales, False en caso contrario
    return caracter in vocales

# Ejemplo de uso
# Solicita al usuario que ingrese un carácter
caracter = input("Ingresa un carácter: ")

# Llama a la función y muestra el resultado
if es_vocal(caracter):
    print(f"{caracter} es una vocal.")
else:
    print(f"{caracter} no es una vocal.")
![image](https://github.com/user-attachments/assets/1a70bf7e-166e-45a7-ab43-4553fc2bd6ac)
