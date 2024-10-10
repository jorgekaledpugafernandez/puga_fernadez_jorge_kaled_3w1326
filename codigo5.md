print("puga fernandez jorge kaled")
import math

# Función para calcular el área de un círculo
def area_circulo(radio):
    return math.pi * (radio ** 2)

# Función para calcular el volumen de un cilindro
def volumen_cilindro(radio, altura):
    return area_circulo(radio) * altura

# Ejemplo de uso
radio = float(input("Ingresa el radio del círculo: "))
altura = float(input("Ingresa la altura del cilindro: "))
print(f"Área del círculo: {area_circulo(radio):.2f}")
print(f"Volumen del cilindro: {volumen_cilindro(radio, altura):.2f}")
![image](https://github.com/user-attachments/assets/6738def9-2177-48ad-a2a1-071f55352bc5)
