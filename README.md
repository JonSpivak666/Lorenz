# Sistema de Lorenz y el Caos

Este repositorio contiene un proyecto en Jupyter Notebook que simula y visualiza el comportamiento caótico del sistema de Lorenz. El sistema de Lorenz es conocido por su sensibilidad extrema a las condiciones iniciales y es un ejemplo clásico de un sistema dinámico caótico.

## Descripción

El sistema de Lorenz se define mediante el siguiente conjunto de ecuaciones diferenciales ordinarias:

\[
\begin{cases}
\dot{x} = \sigma (y - x) \\
\dot{y} = x (r - z) - y \\
\dot{z} = xy - bz
\end{cases}
\]

donde \(\sigma\), \(r\), y \(b\) son parámetros positivos. En este proyecto, usamos los valores comúnmente usados para estos parámetros: \(\sigma = 10\), \(r = 28\), y \(b = \frac{8}{3}\).

## Contenido

- `Lorenz.ipynb`: Jupyter Notebook que contiene la simulación y visualización del sistema de Lorenz.
- `README.md`: Este archivo, que describe el contenido del repositorio y cómo usarlo.

## Requisitos

Para ejecutar el notebook, necesitas tener instaladas las siguientes librerías:

- `numpy`
- `matplotlib`
- `scipy`

Puedes instalarlas usando pip:

```bash
pip install numpy matplotlib scipy
