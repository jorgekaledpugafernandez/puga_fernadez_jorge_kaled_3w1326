print("puga fernnadez jorge kaled")
# Función para obtener la longitud de la última palabra en un string
def longitud_ultima_palabra(texto):
    # Separa el texto en palabras usando espacios en blanco y elimina espacios al inicio y al final
    palabras = texto.strip().split()
    # Retorna la longitud de la última palabra, o 0 si no hay palabras
    return len(palabras[-1]) if palabras else 0

# Ejemplo de uso
# Solicita al usuario que ingrese un texto
texto = input("Ingresa un texto: ")
# Calcula la longitud de la última palabra y la imprime
print(f"La longitud de la última palabra es: {longitud_ultima_palabra(texto)}")
![image](https://github.com/user-attachments/assets/b79cbd58-555a-4ad0-933e-b5ae92861907)
