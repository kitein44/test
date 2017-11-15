
#!/usr/bin/python3
nombre = input ("tapez un nombre:")
nombre = int(nombre)
while nombre.isnumeric() == False:
   print("le nombre n'est pas un entier")
   nombre= input("Retapez")
nombre = int(nombre)
if nombre%2 == 0:
    print(nombre, "est pair")
else:
    print(nombre, "est impair")
