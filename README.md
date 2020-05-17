### Trabajo Final del Primer Bimestre - Programación Orientada a Objetos
Necesitamos realizar un sistema de gestión de una inmobiliaria. En la empresa se necesita llevar llegar el registo de construtoras, edificios, departamentos, casas
Una casa tiene propiedades como: 

- propietario (nombres, apellidos, identificacion)
- precio
- ubicación (nombre del barrio, referencia)
- ciudad (nombre ciudad, nombre provincia)
- numero de cuartos
- constructora (nombre constructora)

Un departamento posee características como:
- propietario (nombres, apellidos, identificacion)
- precio
- ubicación (número de casa, nombre del barrio, referencia)
- ciudad (nombre ciudad, nombre provincia)
- nombre de edificio
- ubicacion del departamento en edificio
- constructora (nombre constructora, id de la empresa)


El sistema debe permitir ingresar:
- Propietarios
- Ubicaciones
- Ciudades
- Constructoras
- Casas
- Departamentos

Características:
- Todos los objetos de tipo propietario se deben ingresar y guardar en un archivo llamado propietarios.txt
- Todos los objetos de tipo ubicación se deben ingresar y guardar en un archivo llamado ubicaciones.txt
- Todos los objetos de tipo ciudad se deben ingresar y guardar en un archivo llamado ciudades.txt
- Todos los objetos de tipo constructora se deben ingresar y guardar en un archivo llamado constructoras.txt
- Todos los objetos de tipo casa se deben ingresar y guardar en un archivo llamado casas.txt
  - Para el ingreso de una casa se debe tomar en consideración lo siguiente:
    - El propietario se debe obtener del archivo propietarios.txt a través de la identificacion.
    - La ubicación se debe obtener del archivo ubicaciones.txt a través del número de casa.
    - La ciudad se debe obtener del archivo ciudades.txt a través del nombre de la ciudad.
    - La constructora se debe obtener del archivo constructoras.txt a través del id de la empresa.
- Todos los objetos de tipo departamento se deben ingresar y guardar en un archivo llamado departamentos.txt

