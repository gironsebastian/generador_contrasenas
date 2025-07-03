import random

characters = "+-/*!&$#?=@<>abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

length = int(input("Ingresa la longitud: "))

password = ""

for character in range(length):
    password += random.choice(characters)

print(f"Tu nueva contraseña es: {password}")
