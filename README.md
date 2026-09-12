# Redes Neuronales Básicas

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RubyDayana/redes-neuronales-basicas/blob/main/RedesNeuronalesBasicasRDCARDENAS.ipynb)

Taller de programación de redes neuronales **desde cero** con Python y NumPy, sin librerías de Deep Learning.

**Universidad de Cundinamarca**
**CADI:** Deep Learning — Conceptos
**Estudiante:** Ruby Dayana Cárdenas Gómez
**Docente:** Nidia Stella García Roa

---

## ¿De qué trata?

Se programan tres modelos de redes neuronales línea por línea, para entender qué ocurre por dentro cuando
una red aprende. No se usa TensorFlow, Keras ni PyTorch: únicamente Python y NumPy.

| Modelo | Qué es | ¿Resuelve XOR? |
|---|---|---|
| **Perceptrón** | Una sola neurona con función escalón | No |
| **Red de una capa** | Varias neuronas en paralelo con sigmoide | No |
| **Red multicapa** | Capa oculta + retropropagación | Sí |

## Contenido

0. Glosario de siglas y términos
1. Conceptos: de Machine Learning a Deep Learning
2. Operaciones con NumPy y vectorización
3. El perceptrón: compuertas AND, OR y el problema del XOR
4. Red neuronal de una capa
5. Red neuronal multicapa: retropropagación y solución del XOR
6. Caso aplicado: predecir si un estudiante aprueba
7. Comparación de los tres modelos
8. Conclusiones

## Cómo ejecutarlo

Haz clic en el botón **Open in Colab** y luego en `Entorno de ejecución → Ejecutar todo`.
No hay que instalar nada.

## Resultados

- El perceptrón aprende **AND en 5 épocas** y **OR en 3**, pero en **XOR solo acierta 1 de 4**.
- La red de una capa aprende AND y OR al mismo tiempo (error final 0.0034); en XOR se queda en 0.5 sin decidirse.
- La red multicapa (2 → 4 → 1) resuelve **XOR con 4 aciertos de 4**, bajando el error de 0.2629 a 0.0001.
- En el caso aplicado alcanza **100 % de exactitud** y entrega la probabilidad de aprobar de cada estudiante.

## Archivos

| Archivo | Descripción |
|---|---|
| `RedesNeuronalesBasicasRDCARDENAS.ipynb` | Notebook con todo el desarrollo y sus resultados |
| `README.md` | Este archivo |
