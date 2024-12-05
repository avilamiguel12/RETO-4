# RETO-4

EJERCICIO #1
a = int(input("Ingrese un entero: "))
if a == 97:
  print("El numero ",a, "corresponde a la vocal a en el codigo ASCII")
elif a == 101:
  print("El numero ",a, "corresponde a la vocal e en el codigo ASCII")
elif a ==105:
  print("El numero ",a, "corresponde a la vocal i en el codigo ASCII")
elif a ==111:
  print("El numero ",a, "corresponde a la vocal o en el codigo ASCII")
elif a ==117:
  print("El numero ",a, "corresponde a la vocal u en el codigo ASCII")
else:
  print("El numero", a, "no corresponde a ninguna vocal minuscula en el codigo ASCII")


EJERCICIO #2
a = str(input("Ingrese una cadena de longitud 1: "))
if ord(a) % 2 == 0:
  print("El primer numero del codigo ASCII del caracter", a , "es par")
else:
  print("El primer numero del codigo ASCII del caracter", a , "es impar")


EJERCICIO #3
a = input("Ingrese un carácter: ")
if a>='0' and a<='9':
    print("El número ", a," es un dígito")
else:
    print("El número ", a," no es un dígito")

EJERCICIO #4
a = float(input("Ingrese el primer numero: "))
b = float(input("Ingrese el segundo numero: "))

if a % b == 0:
  print(a, "es multiplo de ", b)
else:
  print(a, "no es multiplo de ", b)


EJERCICIO #5
a=float(input("ingrese un numero: "))

if a>0:
    print("el numero", a," es positivo")
elif a==0:
    print("el numero", a," es neutro para la suma")
else:
    print("el numero", a," es negativo")


EJERCICO #6
x = float(input("Ingrese la coordenada x del punto: "))
y = float(input("Ingrese la coordenada y del punto: "))
h = float(input("Ingrese la coordenada x del centro del círculo: "))
k = float(input("Ingrese la coordenada y del centro del círculo: "))
r = float(input("Ingrese el radio del círculo: "))
if (x - h)**2 + (y - k)**2 <= r**2:
    print("El punto (",x,",",y,") está dentro del círculo.")
else:
    print("El punto (",x,",",y,") NO está dentro del círculo.")


EJERCICIO #7
a=float(input("Ingrese el valor de la primera longitud:"))
b=float(input("Ingrese el valor de la primera longitud:"))
c=float(input("Ingrese el valor de la primera longitud:"))

if a+b>c and b+c>a and a+c>b:
    print("Se puede construir un triangulo con las longitudes", a,",", b,",", c)
else:
    print("NO se puede construir un triangulo con las longitudes", a,",", b,",", c)


EJERCICIO #8
a = input("Ingrese el nombre de un país de América en minúsculas: ")

match a:

  case "bolivia":
    print("Sucre")
  case "peru":
    print("Lima")
  case "honduras":
    print("Tegucigalpa")
  case "ecuador":
    print("Quito")
  case "venezuela":
    print("Caracas")
  case "costa rica":
    print("San José")
  case "nicaragua":
    print("Managua")
  case "brasil":
    print("Brasilia")
  case "canada":
    print("Ottawa")
  case "chile":
    print("Santiago")
  case "guatemala":
    print("Ciudad de Guatemala")
  case "colombia":
    print("Bogotá")
  case "argentina":
    print("Buenos Aires")
  case "mexico":
    print("Cuidad de méxico")
  case "panama":
    print("Panamá")
  case "paraguay":
    print("Asunción")
  case "el salvador":
    print("San Salvador")

  case _:
    print("País no identificado")
