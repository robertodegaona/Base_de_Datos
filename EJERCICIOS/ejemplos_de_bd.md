Reseña la historia de SQL.
![image](https://user-images.githubusercontent.com/103066682/168112565-b9ac4f38-589c-424a-ace7-02f1a0321727.png)}


SQL
Structured Query Language, lenguaje de consulta estructurada, diseñado para administrar y recuperar informacion de sistemas de gestion de bases de datos relacionales.
Originalmente basado en el álgebra relacional y en el cálculo relacional, SQL consiste en un lenguaje de definición de datos, un lenguaje de manipulación de datos y un lenguaje de control de datos. El alcance de SQL incluye la inserción de datos, consultas, actualizaciones y borrado, la creación y modificación de esquemas y el control de acceso a los datos. También el SQL a veces se describe como un lenguaje declarativo, también incluye elementos procesales.
Los orígenes del SQL nos llevan a la década de 1970, cuando en los laboratorios de IBM, se creó el nuevo software de base de datos System R. Y para gestionar los datos almacenados en System R, se creó el lenguaje SQL. En un principio se llamó SEQUEL, un nombre que todavía se utiliza como una pronunciación alternativa para SQL, pero más tarde fue renombrado a sólo SQL.

En 1979, una compañía llamada Relational Software, que luego se convirtió en Oracle, vio el potencial comercial del lenguaje SQL y lanzó su propia versión modificada, denominada Oracle V2.

Ahora en su tercera década de existencia, el lenguaje SQL ofrece una gran flexibilidad a los usuarios soportando bases de datos distribuidas, es decir, bases de datos que se pueden ejecutar en varias redes de ordenadores a la vez. Certificado por ANSI e ISO, el lenguaje SQL se ha convertido en un estándar de lenguaje de consulta de base de datos, siendo la base de una gran variedad de aplicaciones de bases de datos bien establecidos en Internet hoy en día. Sirve tanto para propósitos empresariales como para necesidades académicas y funciona tanto en equipos individuales como en servidores de empresa.

Con el avance en la tecnología de base de datos de aplicaciones basadas en SQL se ha vuelto cada vez más asequible para el usuario normal. Esto se debe a la introducción de diversas soluciones de bases de datos SQL de código abierto como MySQL, PostgreSQL, SQLite, Firebird, y muchos más.  


###Ejemplifica los Gestores de Bases de Datos según el tipo de BD.


Un Sistema Gestor de Base de Datos (SGBD) o DataBase Managenent System (DBMS) es un sistema que permite la creación, gestión y administración de bases de datos, así como la elección y manejo de las estructuras necesarias para el almacenamiento y búsqueda de información del modo más eficiente posible.

En la actualidad, existen multitud de SGBD y pueden ser clasificados según la forma en que administran los datos en:

Relacionales (SQL)
No relacionales (NoSQL)

## relacionales
Este modelo se basa fundamentalmente en establecer relaciones o vínculos entre los datos, imaginando una tabla aparte por cada relación existente con sus propios registros y atributos.

Los principales Sistemas gestores de bases de datos relacionales (SGBD SQL) actualmente son:

* MySQL
Es el sistema gestor de bases de datos relacional por excelencia.
Es un SGBD multihilo y multiusuario utilizado en la gran parte de las páginas web actuales. Además es el más usado en aplicaciones creadas como software libre.
![image](https://user-images.githubusercontent.com/103066682/168115202-5718e4f4-02fb-4b6b-8d24-463194316fb7.png)
Se ofrece bajo la GNU GPL aunque también es posible adquirir una licencia para empresas que quieran incorporarlo en productos privativos (Desde la compra por parte de Oracle se está orientando a este ámbito empresarial).

Las principales ventajas de este Sistema Gestor de Bases de datos son:

Facilidad de uso y gran rendimiento
Facilidad para instalar y configurar
Soporte multiplataforma
Soporte SSL
La principal desventaja es la escalabilidad, es decir, no trabaja de manera eficiente con bases de datos muy grandes que superan un determinado tamaño.

*MariaDB
Este SGBD es una derivación de MySQL que cuenta con la mayoría de características de este e incluye varias extensiones.

Nace a partir de la adquisición de MySQL por parte de Oracle para seguir la filosofía Open Source y tiene la ventaja de que es totalmente compatible con MySQL.

![image](https://user-images.githubusercontent.com/103066682/168115488-f4687c55-0df0-4298-8af0-ef4ba8749e0b.png)

Entre las principales características de este Sistema Gestor de Bases de datos se encuentran:

Aumento de motores de almacenamiento
Gran escalabilidad
Seguridad y rapidez en transacciones
Extensiones y nuevas características relacionadas con su aplicación para Bases de datos NoSQL.
No tiene desventajas muy aparentes salvo algunas pequeñas incompatibilidades en la migración de MariaDB y MySQL o pequeños atrasos en la liberación de versiones estables.

* SQLite
Más que un Sistema Gestor de bases de datos como tal, SQLite es una biblioteca escrita en C que implementa un SGBD y que permite transacciones sin necesidad de un servidor ni configuraciones.

![image](https://user-images.githubusercontent.com/103066682/168115693-70f6eefb-5d16-4ee3-b4ed-13e2dc62fcb8.png)


Es una biblioteca utilizada en multitud de aplicaciones actuales ya que es open source y las consultas son muy eficientes.

Las principales características de SQLite son:

El tamaño, al tratarse de una biblioteca, es mucho menor que cualquier SGBD
Reúne los cuatro criterios ACID (Atomicidad, Consistencia, Aislamiento y Durabilidad) logrando gran estabilidad
Gran portabilidad y rendimiento
La gran desventaja de SQLite es la escalabilidad ya que no soporta bases de datos que sean muy grandes.


* PostgreSQL
Este sistema gestor de base de datos relacional está orientado a objetos y es libre, publicado bajo la licencia BSD.

![image](https://user-images.githubusercontent.com/103066682/168115938-5ffe3089-29db-404b-a295-74992ad7f592.png)

Sus principales características son:

Control de Concurrencias multiversión (MVCC)
Flexibilidad en cuanto a lenguajes de programación
Multiplataforma
Dispone de una herramienta (pgAdmin, https://www.pgadmin.org/) muy fácil e intuitiva para la administración de las bases de datos.
Robustez, Eficiencia y Estabilidad.
La principal desventaja es la lentitud para la administración de bases de datos pequeñas ya que está optimizado para gestionar grandes volúmenes de datos.

*Microsoft SQL Server
Es un sistema gestor de bases de datos relacionales basado en el lenguaje Transact-SQL, capaz de poner a disposición de muchos usuarios grandes cantidades de datos de manera simultánea.

![image](https://user-images.githubusercontent.com/103066682/168116132-a7c7b96f-397c-42e4-8b86-bdb70be159e8.png)



Es un sistema propietario de Microsoft. Sus principales características son:

Soporte exclusivo por parte de Microsoft.
Escalabilidad, estabilidad y seguridad.
Posibilidad de cancelar consultas.
Potente entorno gráfico de administración que permite utilizar comandos DDL y DML.
Aunque es nativo para Windows puede utilizarse desde hace ya un tiempo en otras plataformas como Linux o Docker.
Su principal desventaja es el precio. Cuenta con un plan gratuito (Express) pero lo normal es la elección de alguno de los planes de pago disponibles (Standard, Developer, Enterprise o SQL Azure, la versión de SQL Server en la nube).

##Sistemas Gestores de bases de datos No Relacionales (NoSQL)
Una base de datos no relacional (NoSQL) es aquella base de datos que:

No requiere de estructuras de datos fijas como tablas
No garantiza completamente las características ACID
Escala muy bien horizontalmente.
Se utilizan en entornos distribuidos que han de estar siempre disponibles y operativos y que gestionan un importante volumen de datos.

Para la administración de este tipo de bases de datos, actualmente los principales sistemas gestores de bases de datos (SGBD NoSQL) son:

*MongoDB
Estamos ante el Sistema Gestor de Bases de Datos no relacionales (SGBD NoSQL) más popular y utilizado actualmente.

MongoDB es un SBGD NoSQL orientado a ficheros que almacena la información en estructuras BSON con un esquema dinámico que permite su facilidad de integración.

Empresas como Google, Facebook, eBay, Cisco o Adobe utilizan MongoDB como Sistema Gestor de Bases de datos.

![image](https://user-images.githubusercontent.com/103066682/168116663-3d4dd32d-5a8e-40fd-81bc-1b6f59e9231e.png)

Las principales características de MongoDB son:

Indexación y replicación
Balanceo de carga
Almacenamiento en ficheros
Consultas ad hoc
Escalabilidad horizontal
Open Source
Como desventaja principal, MongoDB no es un SGBD adecuado para realizar transacciones complejas.

* Redis
Redis está basado en el almacenamiento clave-valor. Podríamos verlo como un vector enorme que almacena todo tipo de datos, desde cadenas, hashses, listas, etc.

El principal uso de este SGBD es para el almacenamiento en memoria caché y la administración de sesiones.

![image](https://user-images.githubusercontent.com/103066682/168116908-91230e6e-5231-4f80-8708-39900637d892.png)


Las características principales son:
Atomicidad y persistencia
Gran velocidad
Simplicidad
Multiplataforma

* Cassandra
Al igual que Redis, Cassandra también utiliza almacenamiento clave-valor. Es un SGBD NoSQL distribuido y masivamente escalable.

![image](https://user-images.githubusercontent.com/103066682/168117129-80ebec06-974f-42d6-b983-3238e61857c9.png)

