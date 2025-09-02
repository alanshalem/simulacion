# Simulación Numérica - Curso UDEMM

Este repositorio contiene el material del curso de simulación numérica utilizando diferencias finitas para la resolución de ecuaciones en derivadas parciales (PDEs), organizado en módulos temáticos y cuadernos Jupyter.

---

## Estructura del Proyecto

```
estilos/
    numericalmoocstyle.css
modulo_0/
    00_01_Instalacion.ipynb
    00_02_Jupyter.ipynb
    00_03_Python_intro.ipynb
    00_04_NumPy_matrices.ipynb
    00_05_Python_funciones.ipynb
    00_06_Matplotlib_tutorial.ipynb
    figuras/
        addtopath.gif
        anaconda-download.gif
        cclarge_con_fondo.png
        cclarge.png
        mathjax.gif
        movingcells.gif
        newnotebook.gif
        overwrite.gif
        rendermarkdown.gif
        runandprint.gif
modulo_2/
    CLASES/
        02_01_Conveccion1D.ipynb
        02_02_CondicionCFL.ipynb
    TP/
        TP2_SOL_DIFERENCIAS_FINITAS_PDE_RESOLUCION_1.ipynb
        TP2_SOL_DIFERENCIAS_FINITAS_PDE_RESOLUCION_2.ipynb
modulo_3/
    CLASES/
    TP/
        TP3_PROBLEMAS_DE_ADVECCION_RESOLUCION_2.ipynb
modulo_4/
    CLASES/
        04_01_EcuacionCalor_1D_Explicita.ipynb
        04_02_EcuacionCalor_1D_Implicita.ipynb
        04_03_EcuacionCalor_2D_Explicita.ipynb
        04_04_EcuacionCalor_2D_Implicita.ipynb
        04_05_Crank-Nicolson.ipynb
    TP4/
modulo_5/
    CLASES/
    TP5/
```

---

## Descripción de Carpetas y Archivos

### estilos/
- **numericalmoocstyle.css**: Hoja de estilos para los cuadernos Jupyter, mejora la visualización y formato de los contenidos.

### modulo_0/ - Introducción y Herramientas
- **00_01_Instalacion.ipynb**: Guía para instalar Anaconda, Jupyter y librerías necesarias (`numpy`, `matplotlib`, etc.).
- **00_02_Jupyter.ipynb**: Introducción al entorno Jupyter Notebook, edición, ejecución y trucos.
- **00_03_Python_intro.ipynb**: Fundamentos de Python, variables, estructuras, arrays y bucles.
- **00_04_NumPy_matrices.ipynb**: Uso de NumPy para operaciones matriciales.
- **00_05_Python_funciones.ipynb**: Definición y uso de funciones en Python.
- **00_06_Matplotlib_tutorial.ipynb**: Tutorial de gráficos con Matplotlib.
- **figuras/**: Imágenes y gifs ilustrativos para los cuadernos.

### modulo_2/ - Convección y Estabilidad
- **CLASES/**:
  - **02_01_Conveccion1D.ipynb**: Introducción a la ecuación de advección 1D, discretización y simulación.
  - **02_02_CondicionCFL.ipynb**: Estabilidad numérica, condición CFL, experimentos con malla y paso de tiempo.
- **TP/**:
  - **TP2_SOL_DIFERENCIAS_FINITAS_PDE_RESOLUCION_1.ipynb**: Ejercicios sobre stencils, esquemas explícitos/implícitos, estabilidad y visualización.
  - **TP2_SOL_DIFERENCIAS_FINITAS_PDE_RESOLUCION_2.ipynb**: Ejercicios prácticos de diferencias finitas y análisis de resultados.

### modulo_3/ - Advección y Métodos Avanzados
- **TP/**:
  - **TP3_PROBLEMAS_DE_ADVECCION_RESOLUCION_2.ipynb**: Problemas de advección, métodos de Richtmyer y simulación de tubos de choque.

### modulo_4/ - Difusión y Calor
- **CLASES/**:
  - **04_01_EcuacionCalor_1D_Explicita.ipynb**: Ecuación de calor 1D, método explícito, condiciones de frontera.
  - **04_02_EcuacionCalor_1D_Implicita.ipynb**: Método implícito, sistemas lineales, condiciones de Dirichlet y Neumann.
  - **04_03_EcuacionCalor_2D_Explicita.ipynb**: Difusión en 2D, esquema explícito, visualización con mapas de contorno.
  - **04_04_EcuacionCalor_2D_Implicita.ipynb**: Método implícito en 2D, matrices de bloques, resolución de sistemas.
  - **04_05_Crank-Nicolson.ipynb**: Esquema de Crank-Nicolson, precisión de segundo orden, análisis de convergencia.
- **TP4/**: Ejercicios prácticos sobre los temas del módulo.

### modulo_5/
- **CLASES/** y **TP5/**: Espacio para clases y trabajos prácticos avanzados.

---

## Requisitos

- **Python 3.7+**
- **Jupyter Notebook**
- **NumPy**
- **Matplotlib**
- **SymPy** (opcional para ejercicios simbólicos)
- **Anaconda** (recomendado para instalación sencilla)

---

## Instalación

1. Instale [Anaconda](https://www.anaconda.com/products/distribution).
2. Ejecute en terminal:
   ```bash
   conda install jupyter numpy scipy sympy matplotlib
   ```
3. Inicie Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Abra los cuadernos `.ipynb` desde el navegador.

---

## Uso

- Cada módulo contiene cuadernos con teoría, ejemplos y ejercicios.
- Ejecute las celdas de código para simular y visualizar resultados.
- Modifique parámetros para experimentar con estabilidad, precisión y condiciones de frontera.

---

## Créditos y Licencia

Material educativo para el curso de simulación numérica UDEMM.  
Imágenes y estilos incluidos para