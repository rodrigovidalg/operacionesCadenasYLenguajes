# 🧠 Proyecto: Operaciones con Cadenas y Lenguajes

Este proyecto implementa un sistema en Java con interfaz gráfica (Swing) que permite realizar operaciones clave con **cadenas**, **lenguajes formales**, y la **simulación de un autómata finito determinista (AFD)**, en el contexto del curso **Lenguajes Formales y Autómatas**.

---

## 📌 FASE III – Desarrollo del sistema

### ✅ Introducción

En esta fase se desarrolló una aplicación gráfica en Java que permite realizar múltiples operaciones relacionadas con **lenguajes formales y autómatas finitos**. El sistema fue implementado utilizando **Apache NetBeans**, con componentes `Swing`, y empaquetado como `.jar` para facilitar su distribución.

El desarrollo permitió aplicar los conceptos vistos en clase de forma práctica, incluyendo alfabetos, cadenas, lenguajes, operaciones entre lenguajes, cerraduras, potencias, inversas, y simulaciones de AFDs.

---

### 🧭 Estructura general

El sistema cuenta con dos módulos principales accesibles desde el menú principal:

- 🔹 **Operaciones con cadenas**
- 🔹 **Operaciones con lenguajes**

Cada módulo permite al usuario ingresar entradas y obtener resultados procesados en tiempo real.

---

### 🔹 Funcionalidades implementadas

#### 📍 Operaciones con cadenas:
- Longitud
- Inversa
- Concatenación
- Potencia (wⁿ)
- Validaciones:
  - Inicia con `0`
  - Contiene `01`
  - Termina con `1`
- Simulación visual paso a paso de un AFD

#### 📍 Operaciones con lenguajes:
- Unión (L1 ∪ L2)
- Intersección (L1 ∩ L2)
- Diferencia (L1 − L2)
- Concatenación (L1 · L2)
- Potencia de lenguaje (Lⁿ)
- Inversa (palabra por palabra)
- Cerradura de Kleene (L*)
- Cerradura positiva (L⁺)

---

### 🚀 Ejecución del sistema

#### Opción 1: Desde consola

```bash
java -jar operacionesCadenasYLenguajes-1.0-SNAPSHOT.jar
