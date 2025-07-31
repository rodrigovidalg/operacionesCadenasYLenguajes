# 🧠 Proyecto: Operaciones con Cadenas y Lenguajes Formales

Este proyecto en Java incluye una **interfaz gráfica (Swing)** para realizar operaciones fundamentales sobre **cadenas**, **lenguajes formales** y la **simulación de autómatas finitos deterministas (AFD)**. Fue desarrollado en el contexto del curso **Lenguajes Formales y Autómatas** y permite aplicar conceptos teóricos de forma práctica.

## 📌 Fase III – Desarrollo del sistema

### ✅ Introducción

Se desarrolló una aplicación gráfica en Java usando **Apache NetBeans** y componentes de **Swing**, empaquetada como un archivo `.jar` para facilitar su distribución y uso. La aplicación permite realizar operaciones sobre alfabetos, cadenas, y lenguajes formales, así como simular el comportamiento de autómatas finitos.

## 🧭 Estructura general

La aplicación dispone de dos módulos principales accesibles desde el menú:

- 🔹 **Operaciones con cadenas**
- 🔹 **Operaciones con lenguajes**

Ambos módulos permiten ingresar datos, ejecutar operaciones y visualizar resultados de forma interactiva y en tiempo real.

## 🔹 Funcionalidades implementadas

### Operaciones con cadenas
- Calcular longitud
- Obtener la inversa
- Concatenación
- Potencia de cadenas (wⁿ)
- Validaciones específicas:
  - Inicia con `0`
  - Contiene la subcadena `01`
  - Termina con `1`
- Simulación visual paso a paso de un AFD

### Operaciones con lenguajes
- Unión (L1 ∪ L2)
- Intersección (L1 ∩ L2)
- Diferencia (L1 − L2)
- Concatenación (L1 · L2)
- Potencia de lenguaje (Lⁿ)
- Inversa (palabra por palabra)
- Cerradura de Kleene (L*)
- Cerradura positiva (L⁺)

## 🚀 Cómo ejecutar el sistema

### Opción 1: Desde consola

    java -jar operacionesCadenasYLenguajes-1.0-SNAPSHOT.jar

### Opción 2: Usando archivo `.bat` (solo Windows)

`programa.bat`

> Asegúrate de tener instalada una versión de **Java 17 o superior** (`java -version`).
