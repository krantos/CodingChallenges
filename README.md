# Metodología de Sistemas

## Implementación de los requisitos

### Requisitos

1.	Cuando se llama a la herramienta con el argumento c devuelve la cantidad de bytes del archivo txt.
```shell
ccwc -c test.txt
342190 test.txt
```

2. Cuando se llama a la herramienta con el argumento l devuelve la cantidad de líneas del arcihvo txt
```shell
ccwc -l test.txt
7145 test.txt
```
### Pasos para instalar el proyecto

1. Descarga el proyecto usando git

```shell
git clone https://github.com/krantos/CodingChallenges.git
```
```shell
cd CodingChallenges
```

2. Asegurarse de que el código compila

```shell
mvn compile
```

3. Asegurarse que existe la siguiente structura de carpetas, si no, crear las carpetas necesarias

```shell
CodingChallenges
|-- pom.xml
`-- src
    |-- main
    |   `-- java
    |   |   `-- ccwc (acá van el código)
    |   `-- resources
    `-- test
        `-- java
        |   `-- ccwc (acá van los tests)
        `-- resources 
```
4. Escribí el código y luego corré los tests con

```shell
mvn test
```
