print("puga fernandez jorge kaled")
# Definición de la función para calcular el total de una factura con IVA
def calcular_total_con_iva(cantidad_sin_iva, porcentaje_iva=21):
    # Calcula el monto del IVA multiplicando la cantidad sin IVA por el porcentaje de IVA
    iva = cantidad_sin_iva * (porcentaje_iva / 100)
    # Retorna la suma de la cantidad sin IVA y el monto del IVA
    return cantidad_sin_iva + iva

# Ejemplo de uso
# Solicita al usuario que ingrese la cantidad sin IVA
cantidad_sin_iva = float(input("Ingresa la cantidad sin IVA: "))
# Solicita al usuario que ingrese el porcentaje de IVA (opcional)
porcentaje_iva_input = input("Ingresa el porcentaje de IVA (presiona Enter para usar 21%): ")

# Verifica si se ingresó un porcentaje de IVA
if porcentaje_iva_input:
    porcentaje_iva = float(porcentaje_iva_input)  # Convierte a float si se ingresó un valor
else:
    porcentaje_iva = 21  # Aplica el porcentaje por defecto

# Calcula el total de la factura llamando a la función
total_factura = calcular_total_con_iva(cantidad_sin_iva, porcentaje_iva)

# Imprime el total de la factura
print(f"El total de la factura, después de aplicar el IVA, es: {total_factura:.2f}")
![image](https://github.com/user-attachments/assets/94c3c2d5-b271-4f10-b39a-83f7af37656d)
![image](https://github.com/user-attachments/assets/8e1ca969-df84-4bb2-b5f5-06276cfeb00b)

