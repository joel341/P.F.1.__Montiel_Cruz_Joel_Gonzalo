# P.F.1.__Montiel_Cruz_Joel_Gonzalo
codigos en tu portafolio y explicando la teoria correspondiente en los archivos Readme.md si es necesario de manera detallada.

#PRIMER EJERCICIO 1.1
print ("Hola mundo")                                 #En este codij solo fue mandar imprimir n saludo en la consola
print (3+4)

![image](https://user-images.githubusercontent.com/79875910/111683636-5bac1280-87eb-11eb-9c9e-71db81f26f13.png)





#EJERCICIO 2.1
PI = 3.1416                                         #infresamos un valor tipo float para que este pueda aser los calculos definimos variables las cuales almacenan formulas
Pedimos el radio
r = float( input('Introduce radio del círculo: ') )
 Calculamos el área y perímetro
a = PI * r * r
p = 2 * PI * r
 Damos los resultados
print('Área =', a)
print('Perímetro =', p)

![image](https://user-images.githubusercontent.com/79875910/111683853-9e6dea80-87eb-11eb-9dd9-2c14c35c174b.png)





#EJERCICIO ext 1_1                                 #solo declaras variables e ingresas el valor de este y luego lo mandas a llamar enla consola
print('Pepito')
print('Cumpleanos: 22 de enero')
edad = 42
print('Tengo', edad, 'anos')
cantante = 'Suzanne Vega'
comida = 'rúcula'
ciudad = 'Barcelona'
print('Me gusta la música de', cantante)
print('Me gusta cenar', comida)
print('Vivo en', ciudad)
![image](https://user-images.githubusercontent.com/79875910/111683991-c8271180-87eb-11eb-97ad-5eb9e55670aa.png)




#EJERCICIO ext 1_2.a    
print('suma de dos enteros')                      #
b = int( input('Entre el dato 2: ') )
suma = a + b
print('La suma vale:' , suma)

![image](https://user-images.githubusercontent.com/79875910/111684080-decd6880-87eb-11eb-8227-0c4fcdea2a08.png)




#EJERCICIO ext 1_2.b    
print('Suma de dos reales')
a = float( input('Entre el dato 1: ') )
b = float( input('Entre el dato 2: ') )
suma = a + b
print('La suma vale:' , suma)

![image](https://user-images.githubusercontent.com/79875910/111684771-bc881a80-87ec-11eb-85cb-303f955cbcb3.png)




#EJERCICIO ext 1_3.b
print('Pruebas de formatos de impresión')
print('--------------------------------\n')
dato1 = 205
dato2 = 205.5
dato3 = 'hola'
print('Entero en bases 10 y 16 : %d %x' % (dato1 , dato1))
print('Entero alineado derecha (6 pos rell 0) : %06i' % (dato1))
print('Real sin formato : %f' % (dato2))
print('Real con dos decimales : %.2f' % (dato2))
print('Real alineado derecha (12 pos 0 decim) : %12.0f' % (dato2))
print('Real alineado derecha (12 pos 2 decim) : %12.2f' % (dato2))
print('Real con formato exponencial : %e' % (dato2))
print('Cadena alin. izquierda (20 pos) : %20s' % (dato3))
print('Cadena alin. derecha (20 pos) : %-20s' % (dato3))

![image](https://user-images.githubusercontent.com/79875910/111684887-e5101480-87ec-11eb-85b1-60c40c53724b.png)




#EJERCICIO ext 1_3
print('Pruebas de formatos de impresión')
print('--------------------------------\n')
dato1 = 333
dato2 = 205.5
dato3 = 'hola'
print(f'Entero en bases 10, 2 y 16 : {dato1} {dato1:b} {dato1:x}')
print(f'Entero alineado derecha (6 pos rell 0) : {dato1:06}')
print(f'Real sin formato : {dato2}')
print(f'Real con dos decimales : {dato2:.2f}')
print(f'Real alineado derecha (12 pos 0 decim) : {dato2:12.0f}')
print(f'Real alineado derecha (12 pos 2 decim) : {dato2:12.2f}')
print(f'Real con formato exponencial : {dato2:e}')
print(f'Cadena alin. izquierda (20 pos rell =) : {dato3:=<20}')
print(f'Cadena centrada (20 pos rell _) : {dato3:_^20}')
print(f'Cadena alin. derecha (20 pos rell .) : {dato3:.>20}')

![image](https://user-images.githubusercontent.com/79875910/111685251-4afc9c00-87ed-11eb-8436-17e42dd9f06d.png)




#EJERCICIO ext 2_2
rint('calcula tu media')
a = int( input('Introduce tu primer numero: ') )
b = int( input('Introduce tu segundo numero: ') )
c = int( input('Introduce tu tercer numero: ') )
media = a+b+c/3
print('la media es', media)

![image](https://user-images.githubusercontent.com/79875910/111685411-80a18500-87ed-11eb-96b7-97df0f705662.png)




#EJERCICIO ext 2_3
print('calculo de dos puntos')
print("ingrese el primer punto cartesiano")
a,b = int(input('Introduce el punto ax : ') ),int(input('Introduce el punto ay: ') )
print("ingrese el segundo punto cartesiano")
c,d = int(input('Introduce el punto bx: ') ),int(input('Introduce el punto by: ') )
#formulas
medio=a+c/2
medio1=b+d/2
print("el nuevo punto en el plano cartesianoes",medio,",",medio1)
print("la media es", media,medio1)

![image](https://user-images.githubusercontent.com/79875910/111685904-13422400-87ee-11eb-8d81-e01d732b170a.png)




#EJERCICIO ext 2_4
//calculo de tiempo
print("favor de ingresar un numero entero")
dato=int(input("ingrese el numero entero"))
print("caragando las conversiones en segundos,dias,semans")
//formula de segundos
segundos=min*6055
//formulas min
min=dias/1440
#formulas dias
dias=dato/24
print("los segundos son:",segundos,"los minutos son:",min,"los dias son")

![image](https://user-images.githubusercontent.com/79875910/111686068-3b318780-87ee-11eb-9589-5ea689d5a650.png)



#EJERCICIO ext 2_5
from subprocess import*
display=check_output(["ls"])
print display

![image](https://user-images.githubusercontent.com/79875910/111686242-72a03400-87ee-11eb-8484-5c6dafa8e0ed.png)




#EJERCICIO ext 3_1
print("ventas")
a=int(input("ingresa los datos de la primera ventaA:"))
b=int(input("ingresa los datos de la segunda ventaB:"))
c=int(input("ingresa los datos de la tercera ventaC:"))
print("Las ventas del producto A son las más elevadas")
if (a>b) or (a>c):
    print("la venta A es la mas Elevada")
print("Ningún producto tiene unas ventas inferiores a 200")

![image](https://user-images.githubusercontent.com/79875910/111687025-6bc5f100-87ef-11eb-8344-0dfcfa30a574.png)



#EJERCICIO ext 3_2
import random  
 minusculas=['a','b','c','d','e','f','g','h','i','j','k','l','m','n','o','p','q','r','s','t','u','v','w','x','y','z']  
 mayusculas=['A','B','C','D','E','F','G','H','I','J','K','L','M','N','O','P','Q','R','S','T','U','V','W','X','Y','Z']  
 todas=minusculas+mayusculas  
 vocales=['a','e','i','o','u']  
 toditas=''.join(todas) #convertimos la lista en un string  
 print(toditas)  
 toditas=toditas.lower()  
 vocalitas=''.join(vocales) #convierte la lista en un string  
 letra=random.choice(todas) #eleginos aleatoriamente una letra de la lista todas  
 #letra=random.randrange(len(todas)) #esto no daría la letra sino el orden  
 print(letra)  
 letra=letra.lower()  
 def vocalConsonante(letrita):  
  if letrita in vocalitas:  
   print(letrita," es vocal.")  
  else:  
   print(letrita," es consonante")  
 vocalConsonante(letra) 
 
 ![image](https://user-images.githubusercontent.com/79875910/111687220-a465ca80-87ef-11eb-8c65-0c88a6b1bddb.png)
 
 
 
 #EJERCICIO ext 3_3
 print("relacion de años de vida deun huamno y un canino")
print("dato Los dos primeros años de vida de un perro equivalen cada uno a diez y medio años humanos, y los siguientes años de vida de un perro equivalen cada uno a cuatro años humanos")
print("cuantos años tendrias en la relacion de vida de un canin?")
años_perro=2
años_persona=10.5
años_perro_v=1
años_persona_v=4
edad=int(input("ingresa tu edad para realizar la relacion canina"))
if(edad>=años_persona)

![image](https://user-images.githubusercontent.com/79875910/111687443-e42cb200-87ef-11eb-8891-3aa1c135ec53.png)




 #EJERCICIO ext 3_4
 i=0
while i<1:
      usuario=input("ingrese su nombre de usuario")
      i=i +1
      if str(usuario)=="Joel":
            print("USUARIO CORRECTO")
            clave=input("ingrese su clave")
            if str(clave)=="SENATI":
                  print("Bienvenido Joel")
                  break
            else:
                  print("CLAVE INCORRECTA")
                  if    i==1:
                        print("INTENTOS AGOTADOS")
                        break
      else:
            print("USUARIO INCORRECTO")
            if    i==1:
                  print("INTENTOS AGOTADOS")


![image](https://user-images.githubusercontent.com/79875910/111687593-0e7e6f80-87f0-11eb-9b86-edd5d187545c.png)






 
 #EJERCICIO ext 3_5
 print("ingrese un numero")
a=int(input(":"))

if(a>0):
   print("el valor es positivo")
elif a<0:
    print("el valor es negativo")
    
else :
    print("el valor es cero")
    
    
 ![image](https://user-images.githubusercontent.com/79875910/111687707-366dd300-87f0-11eb-998c-205ab0ea0d68.png)

 
 
#EJERCICIO ext 3_6
 print("longuitudes de triagulos")
print("comprovacion de los diferentes tipos de tringulos dependiendo de los datos ingresados")
a=int(input("ingresa el primer valor de un lado:"))
b=int(input("ingresa el segundo valor de un lado:"))
c=int(input("ingresa el tercer valor de un lado:"))

if((a==b) and (a==c)):
    print("es un triangulo equilatero")
elif (a==b) or (a==c):
    print("es un triangulo isoseles")
    
elif (a!=b) and (a!=c):
    print("es un trisngulo escaleno")
    
 ![image](https://user-images.githubusercontent.com/79875910/111687813-57cebf00-87f0-11eb-84a0-9d754ff73e3f.png)




#EJERCICIO ext 3_6
print("longuitudes de triagulos")
print("comprovacion de los diferentes tipos de tringulos dependiendo de los datos ingresados")
a=int(input("ingresa el primer valor de un lado:"))
b=int(input("ingresa el segundo valor de un lado:"))
c=int(input("ingresa el tercer valor de un lado:"))

if((a==b) and (a==c)):
    print("es un triangulo equilatero")
elif (a==b) or (a==c):
    print("es un triangulo isoseles")
    
elif (a!=b) and (a!=c):
    print("es un trisngulo escaleno")
    
![image](https://user-images.githubusercontent.com/79875910/111687900-7634ba80-87f0-11eb-8f28-595a1b1076f1.png)



#EJERCICIO ext 3_7
a = float( input('Introduce el primer valor: ') )
minimo = a
maximo = a
b = float( input('Introduce el segundo valor: ') )
if b < minimo:
 minimo = b
else:
 maximo = b
c = float( input('Introduce el tercer valor: ') )
if c < minimo:
 minimo = c
elif c > maximo:
 maximo = c
print('El mínimo es', minimo)


![image](https://user-images.githubusercontent.com/79875910/111688157-b98f2900-87f0-11eb-9149-3ed649f3dd73.png)



#EJERCICIO ext 3_8
dia = int( input('Introduce un día de la semana (entre 1 y 7) : ') )
print('El día es ... ', end='')
if dia == 1:
 print('lunes')
elif dia == 2:
 print('martes')
elif dia == 3:
 print('miércoles')
elif dia == 4:
 print('jueves')
elif dia == 5:
 print('viernes')
elif dia == 6 or dia == 7:
 print('festivo')
else:
 print('incorrecto')
 
 
 ![image](https://user-images.githubusercontent.com/79875910/111688875-f2c79900-87f0-11eb-8f88-0bbb5314cb66.png)





#EJERCICIO ext 3_9
print("calculo de una ecuacion lineal")
print("De la forma  ax+b=0")
a=int(input("ingresar el valor del coeficiente a:"))
b=int(input("ingresar el valor del coeficiente b:"))
#formula
print("valor ingresado",a,"x+",b)
x=-b/a
if (a!=0):
    print("tiene solucion unica")
    print("el valor de X=",x)
elif (a==0) and (b!=0):
    print("con estos datos ingresados no tiene solucion")
    
elif (a==0) and (b==0):
    print("existen infinitas soluciones")

![image](https://user-images.githubusercontent.com/79875910/111688997-1854a280-87f1-11eb-8e2a-04bc6452cdc4.png)




#EJERCICIO ext 3_10
print("tamaño de un tornillo")
t = float (input("favor de ingresar el tamaño del tornillo en CM:"))

if (t>=1) and (t<3):
    print("la mediad para este tornillo es pequeño")
elif(t>=3) and (t<5):
    print("la mediad para este tornillo es mediano")
    
elif(t>=5) and (t<6.5):
    print("la mediad para este tornillo es grande")
elif(t>=6.5) and (t<8.5):
    print("la mediad para este tornillo es muy grande")
else:
    print("fuera de rango admisible")
    
    
![image](https://user-images.githubusercontent.com/79875910/111720940-85cdf680-8824-11eb-999b-5d16c705e325.png)




#EJERCICIO ext 3_11
print('calculo de dos puntos')
print("ingrese el primer punto cartesiano")
a,b = int(input('Introduce el punto ax : ') ),int(input('Introduce el punto ay: ') )

print("ingrese el segundo punto cartesiano")
c,d = int(input('Introduce el punto bx: ') ),int(input('Introduce el punto by: ') )
#formulas
medio=a+c/2
medio1=b+d/2
print("el nuevo punto en el plano cartesianoes",medio,",",medio1)

if(medio>0) and (medio1>0):
    print("esta en el cuadrante I")
elif (medio<0) and (medio>0):
    print("esta en el cuadrante II")
elif(medio<0) and (medio1<0):
    print("esta en el cudrante III")
elif(medio>0) and (medio1<0):
    print("esta en el cuadrante IIII")
    

![image](https://user-images.githubusercontent.com/79875910/111721022-b6ae2b80-8824-11eb-8a54-91e59793b331.png)





#EJERCICIO ext 3_12
a,b,c = [int(x) for x in input('Dame tres valores enteros: ').split(' ')]
r = (a if a < c else c) if a < b else (b if b < c else c)
print('Resultado:', r)

![image](https://user-images.githubusercontent.com/79875910/111721096-d3e2fa00-8824-11eb-9f36-9ddec645ed73.png)






#EJERCICIO ext 3_13
from math import sqrt
A = int(input("Ingrese el coeficiente de la variable cuadrática\n"))
B = int(input("Ingrese el coeficiente de la variable lineal\n"))
C = int(input("Ingrese el término independiente\n"))
x1= 0
x2= 0
if ((B**2)-4*A*C) < 0:
  print("La solución de la ecuación es con números complejos")
else:
  x1 = (-B+sqrt(B**2-(4*A*C)))/(2*A)
  x2 = (-B-sqrt(B**2-(4*A*C)))/(2*A)
  print("Las soluciones de la ecuación son:")
  print(x1)
  print(x2)
  
  
  ![image](https://user-images.githubusercontent.com/79875910/111721154-f07f3200-8824-11eb-82c9-66fe83723958.png)
  
  
  
#EJERCICIO ext 3_14
from math import sqrt
class Ecuaciones2Grado():
    def calcular(self, A, B, C):
        if ((B**2)-4*A*C) < 0:
            print("La solución de la ecuación es con números complejos")
        else:
            x1 = (-B+sqrt(B**2-(4*A*C)))/(2*A)
            x2 = (-B-sqrt(B**2-(4*A*C)))/(2*A)
            print("""\
Las soluciones de la ecuación son:
x1 = {}
x2 = {} """.format(x1, x2))
ec1 = Ecuaciones2Grado()
ec1.calcular(1,-5,6)
ec2 = Ecuaciones2Grado()
ec2.calcular(2,-7,3)

![image](https://user-images.githubusercontent.com/79875910/111721225-10165a80-8825-11eb-84cf-6a1662b2137d.png)



#EJERCICIO ext 3_15
i = 10
 while i > 0:
   print(i)
    i = i - 
    
  ![image](https://user-images.githubusercontent.com/79875910/111721283-2b816580-8825-11eb-9cf8-8bb96e08532a.png)
  
 
#EJERCICIO ext 4_1
 print('Cálculo de la media de una serie de datos')
print('-----------------------------------------')
suma = 0
num = 0
x = float( input('Introduce un valor (0 para acabar) : ') )
while x != 0:
 suma = suma + x
 num = num + 1
 x = float( input('Introduce un valor (0 para acabar) : ') )
print('La media de los elementos es', suma/num)


![image](https://user-images.githubusercontent.com/79875910/111721349-494eca80-8825-11eb-9848-938babc6420c.png)

  

#EJERCICIO ext 4_2
i=0
while i<3:
      usuario=input("ingrese su nombre de usuario")
      i=i +1
      if str(usuario)=="Joel":
            print("USUARIO CORRECTO")
            clave=input("ingrese su clave")
            if str(clave)=="SENATI":
                  print("Bienvenido Andy")
                  break
            else:
                  print("CLAVE INCORRECTA")
                  if    i==3:
                        print("INTENTOS AGOTADOS")
                        break
      else:
            print("USUARIO INCORRECTO")
            if    i==3:
                  print("INTENTOS AGOTADOS")



#EJERCICIO ext 4_4
def factorial(x,n):
 if(n>0):
  x=factorial(x,n-1)
  x=x*n
 else:
  x=1
 return x
n=int(input("ingresa un numero  \n"))
x=1
x=factorial(x,n)
print (x)


![image](https://user-images.githubusercontent.com/79875910/111722622-d4c95b00-8827-11eb-8a6a-3205e7ac02be.png)




#EJERCICIO ext 4_5
print('comparador de numeros')
a=float(input('Escriba un numero:'))
b=float(input('Escriba otro número:'))
if a<b:
    print('Menor: ', a, 'Mayor: ', b)
elif a>b:
    print('Menor: ', b, 'Mayor: ', a)
else:
    print('Los numeros son iguales')
    
![image](https://user-images.githubusercontent.com/79875910/111722684-f1659300-8827-11eb-8546-4f35c16c8082.png)



#EJERCICIO ext 4_6
import random
intentosRealizados = 0
print('¡Hola! ¿Cómo te llamas?')
miNombre = input()
 número = random.randint(1, 20)
 print('Bueno, ' + miNombre + ', estoy pensando en un número entre 1 y 20.')
 while intentosRealizados < 6:
 print('Intenta adivinar.') # Hay cuatro espacios delante de print.
 estimación = input()
estimación = int(estimación)
intentosRealizados = intentosRealizados + 1
if estimación < número:
print('Tu estimación es muy baja.') # Hay ocho espacios delante de print.
if estimación > número:
 print('Tu estimación es muy alta.')
if estimación == número:
 break
if estimación == número:
intentosRealizados = str(intentosRealizados)
stimación != número:
número = str(número)
print('Pues no. El número que estaba pensando era ' + número)

![image](https://user-images.githubusercontent.com/79875910/111722748-122de880-8828-11eb-8482-5fa35d412a6a.png)



#EJERCICIO ext 4_7
import math
 
def es_primo(numero):
    """
    Funcion que determina si un numero es primo
    Tiene que recibir el numero entero
    """
 
    if (numero<=1):
        return False
 
    for i in range(2, math.ceil(math.sqrt(numero))+1):
        if(numero%i==0 and i!=numero):
            return False
    return True
 
while True:
    try:
        numero = int(input("inserta un numero (0) de botellas>> "))
        if numero==0:
            break
        if es_primo(numero):
            print ("\nEl numero %s es aceptable para formar un triangulo" % numero)
        else:
            print ("\nEl numero %s NO es acetable para aplilarlos" % numero)
    except:
        print ("\nEl numero tiene que ser entero")
        
        
![image](https://user-images.githubusercontent.com/79875910/111722833-3b4e7900-8828-11eb-8a5a-6c6744bfe551.png)


#EJERCICIO ext 4_9
a=int(input("ingrsa el primer valor"))
b=int(input("ingrsa el segundo valor"))   
c= b+1

for i in range(c,a):
   i=sum(range(c,a))
   print("la suma")
   print(i)         
   
 ![image](https://user-images.githubusercontent.com/79875910/111722927-61741900-8828-11eb-95e4-f4d6ff88dbe6.png)

