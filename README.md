# EuclidesLab 📟

**Visualizador e Interactivo del Algoritmo de Euclides (Clásico y Extendido)**

EuclidesLab es una aplicación web interactiva de una sola página diseñada para estudiantes y entusiastas de las matemáticas, la computación y la criptografía. Permite visualizar paso a paso el funcionamiento del **Algoritmo de Euclides** para el cálculo del Máximo Común Divisor (MCD) y de los coeficientes de la **Identidad de Bézout** mediante el Algoritmo de Euclides Extendido, así como calcular inversos multiplicativos modulares.

## 🚀 Características

- **Algoritmo Clásico:** Visualización en una tabla interactiva con divisiones sucesivas indicando cocientes, residuos y ecuaciones formales, con el paso de terminación resaltado.
- **Algoritmo Extendido (Identidad de Bézout):** Desglose detallado del cálculo recursivo de coeficientes lineales $x$ e $y$ tales que $A \cdot x + B \cdot y = \text{MCD}(A, B)$.
- **Depurador de Código en Vivo (Tracer):** Un simulador interactivo tipo "IDE" que permite ejecutar el código del algoritmo línea por línea. Muestra los cambios en las variables de memoria interna de la CPU y explica qué está ocurriendo computacionalmente paso a paso.
- **Demostración Criptográfica:** Cálculo automático en tiempo real del **Inverso Multiplicativo Modular** (esencial para algoritmos criptográficos como RSA) cuando los números son coprimos ($\text{MCD} = 1$).
- **Diseño Premium:** Interfaz con efectos Glassmorphism, soporte completo para modo oscuro/claro con persistencia, animaciones fluidas en cascada y diseño 100% responsivo para móviles y ordenadores.

## 🛠️ Tecnologías

- **HTML5** (Semántica y accesibilidad)
- **Tailwind CSS v3** (vía CDN Play oficial)
- **Vanilla JavaScript** (Aritmética matemática de precisión, lógica interactiva y depurador paso a paso)

## 📂 Estructura del Proyecto

El proyecto está autocontenido en un solo archivo para máxima portabilidad y facilidad de ejecución:
- `index.html` - Código unificado (HTML, CSS y JS).
- `README.md` - Documentación del proyecto.

## 💻 Instalación y Uso

No requiere dependencias, servidores locales ni procesos de compilación:
1. Clona este repositorio:
   ```bash
   git clone https://github.com/Porruzz/Criptografia.git
   ```
2. Abre el archivo `index.html` directamente en cualquier navegador web (Chrome, Edge, Firefox, Safari, etc.).
