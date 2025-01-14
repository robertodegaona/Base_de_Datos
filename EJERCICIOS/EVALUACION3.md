
## Práctica 4
### Data warehouse

Objetivo: Demostrar la identificación de los elementos que componen data warehouse y
su esquema

Ejercicio:

1. ¿Qué es un DataWarehouse?(valor 2)

es un sistema de informacion que agrega y combina la informacion de diferentes fuentes en un almacen unico y centralizado para respaldar el analisis de empresarial, mineria de datos e inteligencia artificial

2. Realiza un diseño del modelo en estrella (valor 2)

![image](https://user-images.githubusercontent.com/103066682/171661678-ec1e8575-56db-4eb6-b309-4364450d87a6.png)



3. Realiza un diseño del modelo copo de nieve (valor 2)

![image](https://user-images.githubusercontent.com/103066682/171661933-3e15e285-9535-4fab-962b-414a6dca999b.png)



## Práctica 7
### Funciones en SQL
Objetivo: Demostrar el uso y aplicación en una base de datos para mejorar la gestión

Ejercicio:

1. Calcula el número total de productos que hay en la tabla productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/103066682/171660528-752f020e-9f01-4b7e-8e30-433b8041a0b1.png)


![image](https://user-images.githubusercontent.com/103066682/171662034-c51087fa-86c8-4347-8323-32c8f066212b.png)



2. Muestra el número total de productos que tiene cada uno de los fabricantes. El listado
también debe incluir los fabricantes que no tienen ningún producto. El resultado
mostrará dos columnas, una con el nombre del fabricante y otra con el número de
productos que tiene. Ordene el resultado descendentemente por el número de
productos. (valor 4.5)

![image](https://user-images.githubusercontent.com/103066682/171666907-7c2d4967-7ab4-46b1-a492-a61625694a12.png)

![image](https://user-images.githubusercontent.com/103066682/171666986-cd37efe5-abc8-449a-9c48-823f6455960e.png)


3. Muestra el precio máximo, precio mínimo y precio medio de los productos de cada
uno de los fabricantes. El resultado mostrará el nombre del fabricante junto con los
datos que se solicitan. (valor 4.5)

![image](https://user-images.githubusercontent.com/103066682/171668990-70fc0ce5-a053-4a87-8f13-b6a91582fbf8.png)

![image](https://user-images.githubusercontent.com/103066682/171669075-9e9fd432-f434-40ad-9366-5e47ed5ac3de.png)


4. Muestra el nombre de cada fabricante, junto con el precio máximo, precio mínimo,
precio medio y el número total de productos de los fabricantes que tienen un precio
medio superior a 200€. Es necesario mostrar el nombre del fabricante. (valor 4.5)

![image](https://user-images.githubusercontent.com/103066682/171890324-11fb37e1-22b3-4ae0-bd4f-60519ff26fe7.png)

![image](https://user-images.githubusercontent.com/103066682/171890608-37e908cc-bc95-4bc1-8ed7-09469c7d8779.png)




## Práctica 8.
### Disparadores (Triggers)

Objetivo: Demostrar las operaciones que se realizan en una base de datos.

Ejercicio: Crea una base de datos llamada test que contenga una tabla llamada
alumnos con las siguientes columnas. (valor 18)

Evaluación:

Creación de la base de datos : 9 puntos.

Creación de los Disparadores(Triggers): 9 puntos.

Tabla alumnos:

● id (entero sin signo)

● nombre (cadena de caracteres)

● apellido1 (cadena de caracteres)

● apellido2 (cadena de caracteres)

● nota (número real)

Una vez creada la tabla escriba dos triggers con las siguientes características:

● Trigger 1: trigger_check_nota_before_insert

  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de inserción.
  
  o Si el nuevo valor de la nota que se quiere insertar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere insertar es mayor que 10, se
  guarda como 10.

● Trigger2 : trigger_check_nota_before_update
  o Se ejecuta sobre la tabla alumnos.
  
  o Se ejecuta antes de una operación de actualización.
  
  o Si el nuevo valor de la nota que se quiere actualizar es negativo, se guarda
  como 0.
  
  o Si el nuevo valor de la nota que se quiere actualizar es mayor que 10, se
  guarda como 10.
  
Una vez creados los triggers escribe varias sentencias de inserción y actualización
sobre la tabla alumnos y verifica que los triggers se están ejecutando
correctamente.

https://www.db-fiddle.com/f/k1m7Z8LYwfPBFzdJgazk7S/0
