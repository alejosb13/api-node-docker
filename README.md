
## Convenciones de nombres

- Clases: Las creaciones de clases usaran el formato **Pascal Case**.
    Ej: **user login count** = **UserLoginCount**. 

- Funciones y propiedades: Las creaciones de funciones usaran el formato **Camel Case**.
   
    Ej: **user login count** = **userLoginCount**. 

- Variables: Usaran el formato **Camel Case**.
   
    Ej: **user login count** = **userLoginCount**. 

- Constantes: Usaran el formato **Upper Case**.
   
    Ej: **user login count** = **USERLOGINCOUNT**. 

- Archivos: Las creaciones de archivos usaran el formato **kebab-case** (mismo de angular).
   
    Ej: **user login count** = **user-login-count.js**. 

- Todo lo nombrado anteriormente debe ser en ingles. El proyecto manejara solo el idioma ingles.
- Realizar buenas practicas nombrando las variables, funciones, clases y archivos. 
- Cualquier duda comunicarse en el grupo y veremos que correcciones o cambios realizamos. 




## Secciones


### Seccion 1: Docker
Configura un ambiente en docker por api que permita ejecutar un entorno web. El contenedor de la 
base de datos debe ser diferente al que contenga tu aplicación. ej: Contenedor 1: Node (API Libros), contenedor 2: Mysql (DB Libreria), contenedor 3: Node (API Facturacion), contenedor 4: Mysql (DB facturacion)

### Seccion 2: Conexion base de datos
Crear conexión con base de datos utilizando sequelize.js para manejar modelos y migraciones a la hora de levantar el entorno.

#### DB Libreria
- libros (año de lanzamiento, titulo, descripcion, cantidad, fecha creacion,fecha modificacion, precio) 
- usuarios (nombre, apellido, email, contraseña, edad, role, fecha creacion y fecha modificacion ) 
- roles (nombre, fecha creacion y fecha modificacion ) 

#### DB facturacion
- facturas ( numero,total facturado, fecha creacion y fecha modificacion) 
- factura detalles ( factura, producto, cantidad, precio por unidad, precio total, fecha creacion y fecha modificacion)
- usuarios (nombre, apellido,email, contraseña, fecha creacion y fecha modificacion)
