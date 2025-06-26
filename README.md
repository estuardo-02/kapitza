# Kapitza Inverted Pendulum - MATLAB Simulation

Este repositorio contiene una simulación en MATLAB del péndulo invertido de **Kapitza**, modelado a través de un conjunto de ecuaciones dinámicas no lineales.

## 🎥 Video explicativo (en español)

Puedes ver una explicación detallada de este sistema en el siguiente video de YouTube:  
📺 [https://youtu.be/EAG9uApAa9A](https://youtu.be/EAG9uApAa9A)

## 🧠 Descripción del sistema

El péndulo de Kapitza es un péndulo invertido cuyo punto de suspensión vibra rápidamente hacia arriba y hacia abajo, lo que puede estabilizarlo en su posición invertida de forma contraintuitiva.

Las ecuaciones del sistema en coordenadas de estado son las siguientes:

\[
\begin{aligned}
    \dot{x}_1 &= x_2 \\
    \dot{x}_2 &= -C_k \sin(x_1) + \frac{\sin(2x_1)}{4}
\end{aligned}
\]

donde:

\[
C_k = \frac{4g}{L \epsilon^2 \omega^2}, \quad \epsilon = \frac{2\delta}{L}
\]

- \( x_1 \): ángulo del péndulo  
- \( x_2 \): velocidad angular  
- \( g \): gravedad  
- \( L \): longitud del péndulo  
- \( \omega \): frecuencia de vibración  
- \( \delta \): amplitud de vibración

## 📂 Contenido del repositorio

- `kapitza_simulation.mlx`: Archivo de MATLAB Live Script que contiene toda la simulación del péndulo, incluyendo visualización y análisis.

## 🚀 Cómo usarlo

1. Abre el archivo `.mlx` en MATLAB (preferiblemente MATLAB R2020 o superior).
2. Ejecuta el script paso a paso o completamente para ver la simulación y los resultados.
3. Asegúrate de tener habilitado el motor gráfico de MATLAB para visualizar la animación.

## 📌 Requisitos

- MATLAB (recomendado: R2020 o posterior)
- Live Editor habilitado para visualizar archivos `.mlx`

## 📜 Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

---

Desarrollado con fines educativos por [Tu Nombre Aquí].
