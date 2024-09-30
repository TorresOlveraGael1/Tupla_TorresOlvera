# Tupla_TorresOlvera

Torres Olvera Gael

En este codigo hicimos uso de la funcion Tuple
#Creando el tuple
thistuple = ("apple", "banana", "cherry", "pineapple", "kiwi")
print(thistuple)

#Tuple con miembros duplicados 
thistuple = ("apple", "banana", "cherry", "apple", "banana", "cherry")
print(thistuple)

#Contanto los miembros del tuple
thistuple = ("apple", "banana", "cherry", "pineapple", "kiwi")
print(len(thistuple))

#Diferencia de cuando si es tuple y cuando no lo es 
thistuple = ("apple", "pineapple", "kiwi",)
print(type(thistuple))

#No es un tuple
thistuple = ("apple")
print(type(thistuple))

#Dandolea los tuples unas variables 
tuple1 = ("apple", "banana", "cherry")
tuple2 = (1, 5, 7, 9, 3)
tuple3 = (True, False, False)

#Combinando los tipos de datos en los tuples
tuple1 = ("abc", 34, True, 40, "male", 2.0, False)
print(tuple1)

#Tipo de datos de un tuple
mytuple = ("apple", "banana", "cherry", "pineapple", "kiwi")
print(type(mytuple))

#Utilizando el metodo tuple para crear uno
thistuple = tuple(("apple", "banana", "cherry", "pineapple", "kiwi"))
print(thistuple)
