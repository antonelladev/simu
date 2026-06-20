# 🚀 Sistema Integrado de Ingeniería (SII)

Bienvenido al **Sistema Integrado de Ingeniería (SII)**. Este es un software de consola desarrollado en **C++** diseñado para centralizar la gestión de rendimiento académico y la simulación de análisis de circuitos básicos (Ley de Ohm). 

El proyecto está estructurado de forma limpia, modular y enfocada en la eficiencia a través de estructuras de datos nativas (`struct`).

---

## 🛠️ Características Principales

*   **Gestión Académica Avanzada:** Permite el registro de estudiantes, evaluación detallada por tres momentos académicos independientes, cálculo automatizado de promedios y validación de estados de aprobación.
*   **Simulador Eléctrico (Ley de Ohm):** Módulo interactivo capaz de resolver ecuaciones de circuitos para hallar Voltaje (V), Corriente (I) o Resistencia (R), incluyendo prevención de errores matemáticos (división entre cero).
*   **Analizador de Métricas Globales:** Genera reportes estadísticos en tiempo real evaluando el rendimiento del grupo frente a un umbral de excelencia del **70%**.
*   **Interfaz Interactiva:** Flujo de usuario continuo controlado por bucles maestros y submenús anidados en consola.

---

## 📂 Arquitectura del Código

El código se compone de ~200 líneas optimizadas con los siguientes elementos clave:

*   **`struct Estudiante`**: Almacena de forma agrupada los datos de identidad, notas parciales y estados lógicos del alumno.
*   **`struct Circuito`**: Define las variables físicas fundamentales para la simulación de hardware.
*   **Flujos de control avanzados**: Implementación de estructuras `switch` anidadas dentro de ciclos condicionales `while` para evitar la finalización abrupta del programa.

---

## 🚀 Instrucciones de Ejecución

Para compilar y ejecutar este programa en tu entorno local, asegúrate de tener un compilador de C++ instalado (como `GCC/G++`).

### 1. Compilación
Abre tu terminal en la carpeta donde guardaste el archivo `main.cpp` y ejecuta:
```bash
g++ -o SistemaIngenieria main.cpp
