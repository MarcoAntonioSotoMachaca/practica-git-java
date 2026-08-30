# Práctica 1 - Git, GitHub y fundamentos de Java

## Datos del entorno

- Java: 26.0.2.1 2026-08-18
- Javac: 26.0.2.1
- Git: 2.43.0
- Sistema operativo: Linux
- Editor utilizado: Visual Studio Code

## Preguntas

### 1. ¿Qué función cumple `main`?

El método `main` es el punto de entrada de un programa Java. La ejecución del programa comienza desde este método.

### 2. ¿Qué diferencia existe entre `javac` y `java`?

`javac` compila el código fuente `.java` y genera un archivo `.class`.

`java` ejecuta el programa compilado utilizando la máquina virtual de Java.

### 3. ¿Qué archivo se genera después de compilar?

Después de ejecutar:

`javac Main.java`

se genera:

`Main.class`

### 4. ¿Por qué el archivo se llama `Main.java`?

Porque la clase pública se llama `Main`. En Java, el nombre del archivo debe coincidir con el nombre de la clase pública.

### 5. ¿Qué ocurre si la clase se llama `Programa` pero el archivo se llama `Main.java`?

Si `Programa` está declarada como clase pública, se producirá un error de compilación porque el archivo debería llamarse `Programa.java`.