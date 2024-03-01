print("Bienvenido!")
nombre = input("Ingrese su nombre: ")
edad = int(input("Ingrese su edad: "))
print(nombre, "tiene", edad, "años de edad")

####

puntos_partidos_ganados = 3 
puntos_partidos_empatados = 1
puntos_partidos_perdidos = 0 
partidos_jugados = 20

partidos_ganados = int(input("¿Cuantos partidos gano el equipo?: "))
partidos_empatados = int(input("¿Cuantos partidos empato el equipo?: "))
partidos_perdidos = int(input("¿Cuantos partidos perdio el equipo?: "))

puntos_totales = (partidos_ganados * puntos_partidos_empatados 
                  + partidos_empatados * puntos_partidos_empatados 
                  + partidos_perdidos * puntos_partidos_perdidos)

promedio = puntos_totales / partidos_jugados 

print("El promedio de puntos totales es: ", promedio)

####

# Ejercicio n1
nota_1 = float(input("Ingrese su nota N1: "))
nota_2 = float(input("Ingrese su nota N2: "))
nota_3 = float(input("Ingrese su nota N3: "))
nota_final = nota_1 * 0.2 + nota_2 * 0.3 + nota_3 * 0.5 # te ahorras / 100
#nota_final = (nota_1 * 20 / 100) + (nota_2 * 30 / 100) + (nota_3 * 50 / 100)
print("Tu promedio final es de: ", nota_final) 

# Ejercicio n2
nota_1 = float(input("Ingrese su nota n1: "))
nota_2 = float(input("Ingrese su nota n2: "))
nota_3 = float(input("Ingrese su nota n3: "))

promedio_notas = (nota_1 + nota_2 + nota_3) / 3 # para calcular el promedio total
print("Su promedio de notas es: ", promedio_notas) 


print("cadena con/n salto de linea")
#cadena
#con salto de linea     

palabra = "Python"
print(len(palabra))
