# Proyecto del Segundo Cuatrimestre Fundamentos de Programación (Curso  \<21\>/\<22\>)
Autor/a: \<nombre del autor\>   uvus:\<uvus del autor\>

El dataset recogerá datos de la aplicación Instagram de cieertos usuarios aleatorios para determinar si son perfiles falsos

## Estructura de las carpetas del proyecto

* **/src**: Contiene los diferentes archivos que forman parte del proyecto. Debe estar estructurado en los siguentes paquetes
  * **fp.\<tipos.instagram\>**: Paquete que contiene los tipos del proyecto.
  * **fp.\<tipos.instagram\>.test**: Paquete que contiene las clases de test del proyecto.
  * **fp.common**: Paquete que contiene los tipos auxiliares del proyecto
  * **fp.utiles**:  Paquete que contiene las clases de utilidad. 
* **/data**: Contiene el dataset o datasets del proyecto
    * **\<InstagramBOT.csv\>**: Añade una descripción genérica del dataset.
    *     
## Estructura del *dataset*

Los datos contenidos en el dataset han sido generados con la herramienta de makroo, ya que el dataset original contenía carácteres extraños.

Cuenta, fechaCreacion, numSeguidores, numSeguidos, genero, numPublicaciones, version

URL del dataset original: http://kaggle.com/bugrayan/instagram-fake-followers

El dataset está compuesto por \<N\> columnas, con la siguiente descripción:

* **\<Cuenta>**: de tipo \<String\>, representa el nombre de usuario de la cuenta
* **\<fechaCreacion**: de tipo \<LocalDate\>, representa la fecha de la creacion de la cuenta
* **\<numSeguidores>**: de tipo \<Integer\>, representa el numero de seguidores de la cuenta
* **\<numSeguidos>**: de tipo \<Integer\>, representa el numero de seguidos de la cuenta
* **\<genero>**: de tipo \<Enum\>, representa el genero del usuario
* **\<numPublicaciones>**: de tipo \<Integer\>, representa el numero de publicaciones de la cuenta
* **\<version>**: de tipo \<Double\>, representa la version de la aplicacion

....

## Tipos implementados

se implementa el tipo Bot de tipo \<Boolean>\ que nos permitirá saber si el usuario es sospechoso de ser falso

### Tipo Base

El tipo base consta de todos los datos del csv para su lectura y comprension

**Propiedades**:

- _propiedad1_, de tipo \<Tipo1\>, consultable. 
- _propiedad2_, de tipo \<Tipo2\>, consultable y modificable. 
- ...
- 
**Constructores**: 

- C1: Descripción del constructor 1.
- C2: Descripción del constructor 2.
- ...

**Restricciones**:
 
- R1: Descripción de la restricción 1.
- R2: Descripción de la restricción 2.
- ...
- 
**Criterio de igualdad**: Describir el criterio de igualdad

**Criterio de ordenación**: Describir el criterio de ordenación (si lo hay).

**Otras operaciones**:
 
-	_método 1_: Descripción del método 1.
- ...

#### Tipos auxiliares
Descripción de los tipos auxiliares que sean necesarios añadir al proyecto.

### Factoría
Descripción breve de la factoría.

- _método 1_: Descripción del método 1.
-	_método 2_: Descripción del método 2.

### Tipo Contenedor

Descripción breve del tipo contenedor.

**Propiedades**:

- _propiedad1_, de tipo \<Tipo1\>, consultable. 
- _propiedad2_, de tipo \<Tipo2\>, consultable y modificable. 
- ...
- 
**Constructores**: 

- C1: Descripción del constructor 1.
- C2: Descripción del constructor 2.
- ...

**Restricciones**:
 
- R1: Descripción de la restricción 1.
- R2: Descripción de la restricción 2.
- ...
- 
**Criterio de igualdad**: Describir el criterio de igualdad

**Criterio de ordenación**: Describir el criterio de ordenación (si lo hay).

**Otras operaciones**:
 
-	_método 1_: Descripción del método 1.
- ...
