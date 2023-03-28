# ¿Programando por séptima vez?

## Ejercicio #1
Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.
```python
n:int=1
cuadrado=n**2
while(n<=100):
    print("El cuadrado de " + str(n) + " es " + str(cuadrado))
    n =n+1
    cuadrado= (n)**2
```
[![](https://mermaid.ink/img/pako:eNpFkMsKwjAQRX8lzMonVJfFB2JbdeFKd42L0EQbtBOJKSKlP-bWH3PSVsxikjn3XphMBZmRCkI438wzy4V17BhxZP6sejvUmTb9tl-x8XjB1il-3oWyhil0dJ1acd2IUYrzSUeihsQVzuaTIFjWLY2JHr2QpDgYTDtv0ng3lMbhL78hFP9DiXdse4nGbhxfYQQ0SiG0pB9UnnBwuSoUh5CeUtgrB441-UTpzOGFGYTOlmoE5V0KpyItLlYUEJ7F7UFUSe2M3bcraTZTfwEYjFOz?type=png)](https://mermaid.live/edit#pako:eNpFkMsKwjAQRX8lzMonVJfFB2JbdeFKd42L0EQbtBOJKSKlP-bWH3PSVsxikjn3XphMBZmRCkI438wzy4V17BhxZP6sejvUmTb9tl-x8XjB1il-3oWyhil0dJ1acd2IUYrzSUeihsQVzuaTIFjWLY2JHr2QpDgYTDtv0ng3lMbhL78hFP9DiXdse4nGbhxfYQQ0SiG0pB9UnnBwuSoUh5CeUtgrB441-UTpzOGFGYTOlmoE5V0KpyItLlYUEJ7F7UFUSe2M3bcraTZTfwEYjFOz)

## Ejercicio #2
Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.
```python
i : int = 0 
while(i <= 999): 
  i += 1 
  if i%2==0: 
    continue
  print(i) 
i : int = 0 
while(i <= 999): 
  i += 1 
  if i%2>0: 
    continue
  print(i) 
```
[![](https://mermaid.ink/img/pako:eNpdkU1OwzAQha9ijYTUilYq7BIRUNUkbfrDhu4SFlbi0hGNjVxHCEW5GFsuxthOg6gXceZ74zdPdgulqgSEcDipz_LItWH7uJDMrvkok1iiGvt6zqbTR7bI5c93LbRiQhraXr24cGKcYzTrSexI0uJDFATBU-dpQnRvhbTFm_soml2ElITUCssce4fUt2a-Wjq_FU3A27u-Y0Uo-TN257NRipLVSPE0P_fZM1LWV1HW3n5zFWTj8XaIsaVq92_szrqxwcWOfbZTx4ODQ76yX5gAXVnNsaKbbi0pwBxFLQoI6bfi-r2AQnbUxxujXr5kCaHRjZhA81FxI2Lkb5rXEB746UxUVGiU3vmncy_Y_QL16H3k?type=png)](https://mermaid.live/edit#pako:eNpdkU1OwzAQha9ijYTUilYq7BIRUNUkbfrDhu4SFlbi0hGNjVxHCEW5GFsuxthOg6gXceZ74zdPdgulqgSEcDipz_LItWH7uJDMrvkok1iiGvt6zqbTR7bI5c93LbRiQhraXr24cGKcYzTrSexI0uJDFATBU-dpQnRvhbTFm_soml2ElITUCssce4fUt2a-Wjq_FU3A27u-Y0Uo-TN257NRipLVSPE0P_fZM1LWV1HW3n5zFWTj8XaIsaVq92_szrqxwcWOfbZTx4ODQ76yX5gAXVnNsaKbbi0pwBxFLQoI6bfi-r2AQnbUxxujXr5kCaHRjZhA81FxI2Lkb5rXEB746UxUVGiU3vmncy_Y_QL16H3k)

## Ejercicio #3
Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado.
```python
n=int(input("Ingresa un número mayor o igual a 2:"))
i=n
while i>=2:
 if i%2==0:
        print (i )
 i -=1
 ```
[![](https://mermaid.ink/img/pako:eNpNkMFqwzAMhl_FCAYd1LD1GHBGaZouhZ3WW9KDsd1VLLE3z2aMkBfbdS82xQ5jxli_Pv0gSyMopw0UcOndp7pKH9ip6iybz3bVWFTobnO-ZZyXbNfan-_BeMeMDRTOubhLxaq1ImOmouzfIxovF0eVHPsWhV3InkA9Yik2D1MmNecngocRbzZC3P3DdMvHVY12-cwhO5sWz38geVhOG9JH6oX8fjEc525Jzg-sgYYYJGqafZxJB-FqBtNBQVJL_9pBZyfyyRjc85dVUAQfzRrim5bBVChfvByguMj-g6jRGJx_ystMO51-AWpYZb4?type=png)](https://mermaid.live/edit#pako:eNpNkMFqwzAMhl_FCAYd1LD1GHBGaZouhZ3WW9KDsd1VLLE3z2aMkBfbdS82xQ5jxli_Pv0gSyMopw0UcOndp7pKH9ip6iybz3bVWFTobnO-ZZyXbNfan-_BeMeMDRTOubhLxaq1ImOmouzfIxovF0eVHPsWhV3InkA9Yik2D1MmNecngocRbzZC3P3DdMvHVY12-cwhO5sWz38geVhOG9JH6oX8fjEc525Jzg-sgYYYJGqafZxJB-FqBtNBQVJL_9pBZyfyyRjc85dVUAQfzRrim5bBVChfvByguMj-g6jRGJx_ystMO51-AWpYZb4)

## Ejercicio #4
En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18:9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a la de A.
```python
A = 25e+6
B = 18.9e+6
año = 2022 
while B < A: 
 print(str(año) + ":" + "Poblacion del pais A:" + str(A) + " y " + "Poblacion del pais B:" + str(B))
 A=A+(A*0.02) 
 B=B+(B*0.03)
 año +=1 
print("Este año la poblacion B sobrepaso la poblacion A.") 
print(str(año) + ":" + "Poblacion del pais A:" + str(A) + " y " + "Poblacion del pais B:" + str(B))
```
## Ejercicio #5
Imprimir el factorial de un número natural n dado.
```python
def factorial(n:int)->int:
   if n==0 or n==1:
            resultado=1
   elif n>1:
            resultado=n*factorial(n-1)
   return resultado
if __name__:"__main__"
n=int(input("Ingrese un numero natural:"))
factorial=factorial(n)
print("El factorial del numero "+ str(n)+ " es "+ str(factorial))
```
## Ejercicio #6
Implementar un algoritmo que permita adivinar un número dado de 1 a 100, preguntando en cada caso si el número es mayor, menor o igual.
```python
import random 
n = random.randint(1, 100)   
numero: int = int(input("Ingrese número de 1 a 100 que considera es el número que tiene el programa: ")) 

while (1<=numero<=100): 
    if n==numero: 
        print("Adivinaste el número") 
        break 
    if numero>n: 
        numero = int(input("El número es MENOR, inserte un nuevo número: ")) 
    if numero<n: 
        numero = int(input("El número es MAYOR, inserte un número nuevo: "))
print("El número que ingresaste fue: " + str(numero)) 
print("El número aleatorio fue: " + str(n)) 
```

## Ejercicio #7
Implementar un programa que ingrese un número de 2 a 50 y muestre sus divisores.
```python
n: int = int(input("Ingrese un número entre 2 y 50: "))
divisor: int = 1 
while (2<=n<=50) and divisor<=n:  
    if n%divisor == 0: 
        print ("El número "+ str(divisor) + " es un divisor de "+ str(n))
    divisor +=1
 ```
 
 ## Ejercicio #8
 Implementar el algoritmo que muestre los números primos del 1 al 100. nota: use funciones
```python
def primo():                
    n = 1                   
    while (n<=100):       
        i = 1              
        x = 0               
        while i <= n:      
            if n%i==0:      
                x = x + 1   
            i = i + 1       
        if x == 2:          
            print(n)       
        n = n + 1           

primo()    
```





