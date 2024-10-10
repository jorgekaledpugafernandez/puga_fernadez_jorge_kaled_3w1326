print("puga fernandez jorge kaled")
# Función para verificar si la dirección de email es válida
def es_email_valido(email):
    # Retorna True si el email contiene '@', False en caso contrario
    return '@' in email

# Ejemplo de uso
# Solicita al usuario que ingrese su dirección de email
email = input("Ingresa tu dirección de email: ")

# Verifica si el email es válido usando la función
if es_email_valido(email):
    # Mensaje si la dirección de email es válida
    print("La dirección de email es válida.")
else:
    # Mensaje si la dirección de email no es válida
    print("La dirección de email no es válida.")
![image](https://github.com/user-attachments/assets/bc75af8b-0724-4d43-8836-d29a2ab35517)
