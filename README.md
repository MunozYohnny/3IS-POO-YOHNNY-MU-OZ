# 3IS-POO-YOHNNY-MU-OZ
YOHNNY HERNEY MUÑOZ ARREDONDO - 2DO SEMESTRES - INGENIERIA EN SISTEMAS - PROGRAMACION ORIENTADO A OBJETOS
## Hola Mundo


# PIRAMIDE DE ASTERISCOS INVERTIDOS
for a in range(5):
    for b in range(5-a):
        print(" ", end="")
    ##print("Stop")
    for c in range(a + 1):
        print("*", end="") 
    print() 
## El primer for es para definir el numero de espacio
## El segundo for es para definir que esos espacio estaran de forma derecha a izquierda
## Por ultimo el ultimo for es para ir aumentando los asteriscos como el ejercicio primero
## El ultimo print es para dar un salto de renglon (Este si me toco investigar)
## Curiosidad: En el print("  ", end="") si le ponia el - me salia bien la piramide pero, cuando lo dejaba solo y un solo espacio, me salia diferente, toca ponerle dos espacio para que de la figura.  
