# Retazo-4
=============================================================

El objetivo era resolver el reto 4, el cual consistia en
realizar algoritmos que cumplieran con las necesidades 
planteadas en cada punto.
A continuacion adjunto la imagen del repo del profe Felipe:

============================================================

![image](https://github.com/user-attachments/assets/8190408c-2d62-4ff3-b9fc-7394907d030d)

============================================================

 >-Asi que adjuntare capturas mostrando como estan
 >diseñados los codigos para cumplir con cada punto del reto,
 >los hice todos en un notebook de python en google colab,
 >aunque el ultimo punto no pude inicializarlo en colab ya
 >que este notebook solo usa python 3 y no versiones posteriores,
 >a su vez adjuntare los codigos para que puedan ser copiados y probados.

============================================================

![image](https://github.com/user-attachments/assets/f8a86e40-9f2d-47d4-92bd-6b747a9a7145)

```
n = int (input( " Digite un numero entero del 0 al 255: " ))
list = (97,101,105,111,117)
if n >= 0 and n <=255:
    if n in list:
        print ( "Este numero pertenece a una letra minuscula en el código ASCII y es " +  chr(n))
    else:
        print ( "Este numero no pertence a una letra minúscula en el código ASCII" )
else:
    print ( "Este numero no pertence a ninguna caracter en el código ASCII" )


```

![image](https://github.com/user-attachments/assets/282f7b27-a4b0-4297-8fe3-8e521d551a61)

```
a = float(input("Ingrese el primer numero: "))
b = float(input("Ingrese el segundo numero: "))

if b != 0:
    if a % b == 0:
        print (str(a) + " es multiplo de " + str(b))
    else:
        print (str(a) + " no es multiplo de " + str(b))
else:
    print (" El segundo número debe ser distinto de 0 " )


```

![image](https://github.com/user-attachments/assets/ac80da18-dd44-4e03-af76-5f37efe93b4a)

```
n = (input("Digite una variable cualquiera "))
try:

    n = float(n)

    if n == int(n):
        print("Esta variable es un digito perteneciente a los enteros")
    else:
        print("Esta variable es un digito perteneciente a los reales")
except ValueError:
    print("Esta variable es un caracter")


```

![image](https://github.com/user-attachments/assets/f7539ac0-8634-4407-b128-c2ab4b513ff9)

```
n = (input("Digite una letra o un caracter cualquiera a excepcion de un número "))
ord(n)

if ord(n) % 2 == 0:
    print ( "Su caracter", n,"en codigo ASCII es par" )
else:
    print ( "Su caracter", n,"en codigo ASCII es impar" )


```

![image](https://github.com/user-attachments/assets/af74d55d-b6a8-48a4-bd91-3969551aa303)

```
lang = input("Escriba un pais de america ")

match lang:
  case "colombia":
    print("La capital del hermoso país en el que nací es bogotá")
  case "ecuador":
    print("La capital es quito")
  case "venezuela":
    print("La capital es caracas")
  case "panama":
    print("La capital es panama")
  case "argentina":
    print("La capital es buenos aires")
  case "uruguay":
    print("La capital es montevideo")
  case "paraguay":
    print("La capital es asuncion")
  case "Bolivia":
    print("La capital es sucre")
  case "brasil":
    print("La capital es brasilia")
  case "chile":
    print("La capital es santiago de chile")
  case "peru":
    print("La capital es lima")
  case "surinam":
    print("La capital es parabarimo")
  case "trinidad y tobago":
    print("La capital es puerto españa")
  case "canada":
    print("La capital es otawwa")
  case "mexico":
    print("La capital es ciudad de mexico")
  case "estados unidos":
    print("La capital es washington dc")
  case "costa rica":
    print("La capital es san jose")
  case "honduras":
    print("La capital es tegucigalpa")
  case "el salvador":
    print("La capital es san salvador")
  case "belice":
    print("La capital es belmopan")
  case "nicaragua":
    print("La capital es managua")
  case "guatemala":
    print("La capital es ciudad de guatemala")
  case "barbados":
    print("La capital es bridgetown")
  case "cuba":
    print("La capital es la habana")
  case "bahamas":
    print("La capital es nasau")
  case "antigua y barbuda":
    print("La capital es saint john")
  case "dominica":
    print("La capital es roseau")
  case "granada":
    print("La capital es saint george")
  case "guyana":
    print("La capital es georgetown")
  case "haiti":
    print("La capital es puerto principe")
  case "jamaica":
    print("La capital es kingston")
  case "repiblica dominicana":
    print("La capital es santo domingo")
  case "san cristobal y nieves":
    print("La capital es basseterre")
  case "san vicente y las granadinas":
    print("La capital es kingstwon")
  case "santa lucia":
    print("La capital es castries")
case _:
    print( "Tranquilo yo también estoy aprendiendo geografía." )


```

![image](https://github.com/user-attachments/assets/07ab089d-c9f3-43fc-a69d-f5e43368a310)

```
x = float(input("Ingrese un numero cualquiera "))

if x != 0:
    if x > 0:
        print ("el número", x, "es positivo")
    else:
        print ("el número", x, "es negativo")
else:
    print ("este numero es 0")


```

![image](https://github.com/user-attachments/assets/7726aad6-311b-4007-b21a-a7f0e9467071)

```
print ("A continuacion se le pedirá que introduzca dos números, estos seran las coordenadas (h,k) de el origen de el círculo y posteriormente digitara su radio")
h = float(input("Ingrese la coordenada h: "))
k = float(input("Ingrese la coordenada k: "))
r = float(input("Ingrese el valor del radio de su circulo: "))
x = float(input("Ingrese un punto de coordenadas x que pertenezca a los reales "))
y = float(input("Ingrese un punto de coordenadas y que pertenezca a los reales "))
Circulo = (x-h)**2 + (y-k)**2
Radio_circulo = r**2
if Circulo < Radio_circulo:
    print ( "El punto" , ( x, y), "está dentro del circulo")
elif Circulo == Radio_circulo:
    print ( "El punto" , ( x, y), "está sobre la circunferencia del circulo")
else:
    print ("El punto", ( x, y), "está por fuera del circulo")


```

![image](https://github.com/user-attachments/assets/91a6475d-20d6-4d37-8e4a-4eb8750da26c)

```
A = float(input("Ingrese la longitud de A: "))
B = float(input("Ingrese la longitud de B: "))
C = float(input("Ingrese la longitud de c: "))

if A<=0 or B<=0 or C<=0:
    print ("Las longitudes deben ser positivas")
elif A+B>=C or B+C>=A or C+A>=B:
    print ("Las longitudes si pueden formar un triangulo")


```

============================================================

# NICOLAS RAMIREZ RODRIGUEZ 1000506513
