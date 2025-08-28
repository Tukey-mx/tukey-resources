# Ejercicio: Redes Radiales (RBF)

## 🎯 Objetivo
Implementar una red RBF para clasificación.

---

## 🧩 Instrucciones
1. Genera un dataset con dos clases usando `sklearn.datasets.make_blobs`.
2. Crea una red RBF con:
   - Función gaussiana: `φ(x) = exp(-||x-c||^2 / (2σ^2))`
3. Ajusta los centros `c` con **k-means**.
4. Entrena una regresión logística sobre las salidas.

---

## 🧠 Preguntas
- ¿Cómo elegir el número de centros?
- ¿Qué pasa si σ es muy grande?

---
[Regresar a la página anterior](./DeepLearning.md)

[Regresar al menú principal](../README.md)
