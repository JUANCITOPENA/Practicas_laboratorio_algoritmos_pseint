# 💻 pseint_algoritmos_studio

<p align="center">
  <img src="https://img.shields.io/badge/PSeInt-Algoritmos-2563eb?style=for-the-badge&logo=codeforces&logoColor=white" alt="PSeInt" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JS" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap 5" />
</p>

<p align="center">
  <b>Simulador interactivo web, visor de diagramas de flujo y entorno de ejecución para los 12 algoritmos fundamentales de PSeInt.</b>
</p>

<p align="center">
  <a href="#-demostración-en-vivo">Demo</a> •
  <a href="#-características-principales">Características</a> •
  <a href="#-lista-de-algoritmos">Ejercicios</a> •
  <a href="#-guía-de-entrega-rar">Guía .RAR</a> •
  <a href="#-instalación-y-uso">Instalación</a>
</p>

---

## 📖 Descripción del Proyecto

**`pseint_algoritmos_studio`** es una plataforma educativa de una sola columna diseñada para estudiantes y entusiastas de la programación que cursan **Introducción a la Lógica de Programación y Algoritmos**.

Permite visualizar la sintaxis de pseudocódigo en PSeInt, inspeccionar dinámicamente sus **diagramas de flujo vectoriales (SVG)** con la simbología y colores oficiales de PSeInt, y simular la consola de ejecución paso a paso sin necesidad de instalar software adicional.

---

## ✨ Características Principales

* 🎯 **Diseño 100% Vertical (Sin pantallas divididas):** Cada ejercicio cuenta con su propio flujo continuo (Enunciado $\rightarrow$ Código $\rightarrow$ Diagrama $\rightarrow$ Consola interactiva).
* 📊 **Diagramas de Flujo Interactivos (SVG):** Se iluminan en tiempo real resaltando el camino verdadero (`V`) o falso (`F`) según los datos ingresados en el simulador.
* 🖥️ **Consola de Ejecución Estilo PSeInt:** Simula salidas de terminal con comandos reales (`*** Ejecución Iniciada. ***`, entradas con `>` y resultados en verde/amarillo/rojo).
* 📋 **Copiado Rápido con un Clic:** Botón integrado para copiar al portapapeles el pseudocódigo limpio de cualquier ejercicio.
* 🔍 **Buscador y Filtros por Categoría:** Encuentra ejercicios por temática (`Entrada/Salida`, `Condicionales Si`, `Operadores Lógicos Y/O/NO`).
* 📦 **Rastreador de Capturas para Entrega Universitaria:** Checkbox y barra de progreso interactiva para marcar los ejercicios listos para el empaquetado final.

---

## 📚 Lista de Algoritmos Incluidos

| # | Algoritmo | Categoría | Concepto Clave |
|---|---|---|---|
| **01** | `SaludoUsuario` | Entrada / Salida | Captura con `Leer` y bienvenida con `Escribir` |
| **02** | `SumaNumeros` | Variables & Aritmética | Asignación (`<-`), suma de enteros y salida |
| **03** | `MayorEdad` | Condicional Simple | Bifurcación `Si ... Entonces ... SiNo` (`>= 18`) |
| **04** | `NumeroPositivo` | Operadores Relacionales | Evaluación de signo numérico (`> 0`) |
| **05** | `EvaluacionAcademica` | Condicional Anidado | Clasificación (`>= 90`, `>= 70`, `< 70`) |
| **06** | `Descuentos` | Decisiones Escalonadas | Aplicación de descuentos (20%, 10%, sin descuento) |
| **07** | `AprobacionEstudiante` | Operador Lógico `Y` | Conjunción obligatoria: `asistencia >= 80 Y nota >= 70` |
| **08** | `DescuentoCine` | Operador Lógico `O` | Disyunción: `edad < 12 O edad > 60` |
| **09** | `Inventario` | Operador Lógico `NO` | Negación de booleano: `Si NO disponible Entonces` |
| **10** | `Universidad` | Lógica Combinada | Admisiones y becas con operadores `Y`, `O` y anidamiento |
| **11** | `Contratacion` | Integración Completa | Evaluación laboral con `Y + O + NO + Si Anidado` |
| **12** | `ProyectoFinal` | 🏆 Proyecto Integrador | Clasificación estudiantil con 3 niveles de decisión |

---

## 📦 Guía de Entrega Universitaria (.RAR)

Este repositorio está preparado para facilitar la entrega requerida en plataformas universitarias:

```text
📁 NOMBRE_APELLIDO_EJERCICIOS_BASICO_ALGORITMOS.rar
  ├── 📁 Codigo_PSeInt/
  │     ├── Ejercicio_01.psc
  │     ├── Ejercicio_02.psc
  │     └── ... (hasta el 12)
  └── 📁 Capturas_Ejecucion/
        ├── Ejercicio_01_codigo.png
        ├── Ejercicio_01_ejecucion.png
        └── ...
