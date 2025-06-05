# Taller-Fundamentos-de-Python
Taller – Fundamentos de Python Brayan Maceta

```python
# Ejercicio 1: Intercambio sin variable auxiliar
a = 5
b = 10
print(f"Antes del intercambio: a = {a}, b = {b}")

# Intercambio usando operaciones aritméticas
a = a + b
b = a - b
a = a - b

print(f"Después del intercambio: a = {a}, b = {b}")
```

```python
# Ejercicio 2: Suma de cuadrados
a = 5
b = 3
c = a**2 + b**2
print(f"La suma de los cuadrados de {a} y {b} es: {c}")
```
```python
# Ejercicio 3: Conversión de tipos
numero = 42
print(f"Tipo original: {type(numero)}")

# Convertir a string
numero_str = str(numero)
print(f"Como string: {numero_str}, tipo: {type(numero_str)}")

# Convertir a float
numero_float = float(numero_str)
print(f"Como float: {numero_float}, tipo: {type(numero_float)}")

# Convertir de nuevo a int
numero_int = int(numero_float)
print(f"De vuelta a int: {numero_int}, tipo: {type(numero_int)}")
```

```python
# Ejercicio 4: Redondeo y formato
numero = 17.8567
numero_redondeado = round(numero, 2)
mensaje = f"Resultado: {numero_redondeado}"
print(mensaje)
```

```python
# Ejercicio 5: Concatenación de variables
nombre = "Juan"
edad = 25
mensaje = f"Hola, mi nombre es {nombre} y tengo {edad} años."
print(mensaje)
```

```python
# Ejercicio 6: Cálculo de edad actual
anio_actual = 2025
anio_nacimiento = 1990
edad = anio_actual - anio_nacimiento
print(f"La edad actual es: {edad} años")
```

```python
# Ejercicio 7: Cuenta regresiva con variables
contador = 10
while contador >= 0:
    print(contador)
    contador -= 1
```

```python
# Ejercicio 8: Valor absoluto sin usar abs()
numero = -15
if numero < 0:
    valor_absoluto = -numero
else:
    valor_absoluto = numero
print(f"El valor absoluto de {numero} es {valor_absoluto}")
```

```python
# Ejercicio 9: Incremento/decremento según paridad
n = 7
if n % 2 == 0:
    n += 1
else:
    n -= 1
print(f"El nuevo valor es: {n}")
```

```python
# Ejercicio 10: Máximo entre tres números
a, b, c = 15, 9, 22
maximo = a
if b > maximo:
    maximo = b
if c > maximo:
    maximo = c
print(f"El máximo entre {a}, {b} y {c} es: {maximo}")
```

```python
# Ejercicio 11: Verificación de rango
x = 50
esta_en_rango = 10 <= x <= 100
print(f"¿{x} está entre 10 y 100? {esta_en_rango}")
```

```python
# Ejercicio 12: Comparación de strings (ignorar mayúsculas)
a = "Hola"
b = "hola"
son_iguales = a.lower() == b.lower()
print(f"¿'{a}' y '{b}' son iguales ignorando mayúsculas? {son_iguales}")
```

```python
# Ejercicio 13: Igualdad entre tres variables
x, y, z = 10, 10, 10
son_iguales = x == y == z
print(f"¿Las tres variables son iguales? {son_iguales}")
```

```python
# Ejercicio 14: Presencia en lista
numeros = [2, 4, 6, 8, 10]
x = 6
esta_en_lista = x in numeros
print(f"¿{x} está en la lista {numeros}? {esta_en_lista}")
```

```python
# Ejercicio 15: Divisibilidad por 3 y 5
n = 15
es_divisible = n % 3 == 0 and n % 5 == 0
print(f"¿{n} es divisible por 3 y 5? {es_divisible}")
```

```python
# Ejercicio 16: Números en orden estricto
a, b, c = 5, 10, 15
en_orden = a < b < c
print(f"¿{a}, {b}, {c} están en orden ascendente estricto? {en_orden}")
```

```python
# Ejercicio 17: Comparación doble
x = 15
a = 10
b = 20
esta_entre = a < x < b
print(f"¿{x} está estrictamente entre {a} y {b}? {esta_entre}")
```

```python
# Ejercicio 18: Relación proporcional
a = 20
b = 10
es_doble = a == 2 * b
print(f"¿{a} es exactamente el doble de {b}? {es_doble}")
```

```python
# Ejercicio 19: Cambio de signo si negativo
x = -7
if x < 0:
    x = -x
print(f"El valor positivo es: {x}")
```

```python
# Ejercicio 20: Detección de tipo
x = 3.14
if isinstance(x, int):
    tipo = "entero (int)"
elif isinstance(x, float):
    tipo = "flotante (float)"
elif isinstance(x, str):
    tipo = "cadena (str)"
else:
    tipo = "otro tipo"
print(f"La variable x es de tipo: {tipo}")
```

```python
# Ejercicio 21: ¿Puede votar?
edad = 20
tiene_documento = True
puede_votar = edad >= 18 and tiene_documento
print(f"¿Puede votar? {puede_votar}")
```

```python
# Ejercicio 22: Control de acceso lógico
tiene_pase_vip = False
paga_entrada = True
esta_ebrio = False
puede_entrar = tiene_pase_vip or (paga_entrada and not esta_ebrio)
print(f"¿Puede entrar? {puede_entrar}")
```


```python
# Ejercicio 23: Validación XOR
cond1 = True
cond2 = False
xor = (cond1 or cond2) and not (cond1 and cond2)
print(f"¿Exactamente una condición es verdadera? {xor}")
```

```python
# Ejercicio 24: Validación compuesta múltiple
n = 6
cumple_condicion = n > 0 and (n % 2 == 0 or n % 3 == 0)
print(f"¿{n} es positivo y múltiplo de 2 o 3? {cumple_condicion}")
```

```python
# Ejercicio 25: Condición contradictoria
x = 3
condicion_contradictoria = x > 5 and x < 1
print(f"¿Se cumple la condición contradictoria? {condicion_contradictoria}")
```

```python
# Ejercicio 26: Negación lógica
x = 15
condicion_original = x > 10
condicion_negada = not (x <= 10)
print(f"Condición original: {condicion_original}")
print(f"Condición negada: {condicion_negada}")
```

```python
# Ejercicio 27: Aprobación de estudiante
nota = 3.5
asistencia = 85
aprueba = nota >= 3.0 and asistencia >= 80
print(f"¿El estudiante aprueba? {aprueba}")
```

```python
# Ejercicio 28: Simulación de alarma
temperatura = -2
humedad = 85
alarma = (temperatura < 0 or temperatura > 38) and humedad > 80
print(f"¿Se activa la alarma? {alarma}")
```

```python
# Ejercicio 29: Contraseña segura
contrasena = "Segura123"
es_segura = len(contrasena) > 8 and any(c.isdigit() for c in contrasena)
print(f"¿La contraseña cumple con los requisitos? {es_segura}")
```

```python
# Ejercicio 30: Doble negación lógica
tiene_acceso = False
expresion = not (not tiene_acceso)
print(f"No es falso que no tenga acceso: {expresion}")
```



