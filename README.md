
# 🚗 Proyecto: Gestión de Aparcamiento

Este repositorio contiene el proyecto **GestionAparcamiento**, una aplicación desarrollada en Java como parte de un trabajo grupal de 4 personas para nuestro grado académico.

## 📋 Descripción General
El sistema es una aplicación basada en Programación Orientada a Objetos (POO) diseñada para administrar un aparcamiento. Permite gestionar la entrada, salida y el registro de diferentes tipos de vehículos utilizando conceptos como herencia y polimorfismo.

## 🏗️ Estructura del Código
El código fuente está estructurado dentro del paquete `gestionaparcamiento` y se compone de las siguientes clases principales:

*   **`Vehiculo.java`**: Clase base que define los atributos y métodos genéricos de cualquier vehículo que ingrese al recinto.
*   **`Automovil.java`**: Clase derivada de `Vehiculo` específica para el manejo de coches.
*   **`Camion.java`**: Clase derivada de `Vehiculo` específica para camiones o vehículos pesados.
*   **`Aparcamiento.java`**: Clase encargada de manejar la lógica del espacio, administrando las plazas disponibles, las tarifas y la lista de vehículos estacionados.
*   **`GestionAparcamiento.java`**: Clase principal (Main) que contiene el método de entrada para ejecutar el programa y la interfaz de consola.

## 🛠️ Tecnologías y Entorno
*   **Lenguaje**: Java.
*   **Entorno de Desarrollo (IDE)**: El código está configurado nativamente como un proyecto de **NetBeans** (carpeta `nbproject/`).
*   **Construcción**: Utiliza Apache Ant para la compilación, a través del archivo `build.xml`.
*   **Distribución**: El sistema se compila en un archivo ejecutable llamado `GestionAparcamiento.jar`, ubicado en el directorio `dist/`.

## 📂 Otros Archivos Relevantes
*   **`lista.txt`**: Archivo de texto plano utilizado por el sistema (ideal para lectura de datos iniciales o persistencia básica).
*   **`README.TXT`**: Archivo de notas adicional generado durante la compilación del proyecto.

## 👥 Equipo de Desarrollo
*   Miembro 1 *Roy-Rebuffo*
*   Miembro 2 *mmarcgomez*
*   Miembro 3 *Fabian-Luna-Vicente*
*   Miembro 4 *LeoeParedez*

## 🚀 Cómo ejecutarlo

Para probar la aplicación, tienes dos opciones principales:

**Opción A: Desde el IDE**
1. Importa la carpeta del proyecto directamente en NetBeans.
2. Compila y ejecuta la clase principal `GestionAparcamiento.java`.

**Opción B: Desde la terminal**
1. Abre tu terminal o línea de comandos.
2. Navega hasta el directorio raíz del proyecto y ejecuta el archivo `.jar` ya compilado[cite: 3]:
   ```bash
   java -jar dist/GestionAparcamiento.jar
   ```
