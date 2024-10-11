![image](https://github.com/user-attachments/assets/e8ef0094-60ea-44e7-ae61-c968b69bd7f8)
print("puga fernandez jorge kaled")
import math  # Importamos la biblioteca para funciones matemáticas

def distancia_dirigida(punto_a, punto_b):
    """
    Calcula la distancia euclidiana entre dos puntos.
    
    Parámetros:
    punto_a (tuple): Coordenadas del primer punto (x1, y1).
    punto_b (tuple): Coordenadas del segundo punto (x2, y2).
    
    Retorna:
    float: La distancia entre los dos puntos.
    """
    x1, y1 = punto_a  # Desempaquetamos coordenadas del primer punto
    x2, y2 = punto_b  # Desempaquetamos coordenadas del segundo punto
    return math.sqrt((x2 - x1)**2 + (y2 - y1)**2)  # Calculamos y retornamos la distancia

# Ejemplo de uso
punto_a = (3, 4)
punto_b = (7, 1)
resultado = distancia_dirigida(punto_a, punto_b)
print(f"La distancia entre {punto_a} y {punto_b} es: {resultado:.2f}")
