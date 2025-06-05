# 🧪 Simulación: Hopping Hoop (Aro Saltarín)

Este repositorio contiene una simulación en Python, lista para Google Colab, basada en el experimento físico conocido como **Hopping Hoop**. El objetivo es **predecir si un aro saltará o no** cuando se le añade una masa extra, y cuántos saltos dará en función de dicha masa.

---

## 📐 Descripción del experimento

En este experimento se hace rodar un aro o disco al que se le añade una masa extra interna. Al moverse, este sistema puede realizar **saltos espontáneos** debido a la conversión entre energía potencial, cinética y centrífuga.

### 🔍 Parámetros experimentales

- **Masa del aro:** 124 g (0.124 kg)  
- **Radio del aro:** 14 cm (0.14 m)  
- **Masa extra para 1 salto:** ~51 g (0.051 kg)  
- **Masa extra para 2 saltos:** ~66 g (0.066 kg)  

El código permite **simular el número de saltos** para una masa extra dada, y determinar **los rangos críticos** donde el salto ocurre o no.

---

## 🚀 ¿Qué incluye este repositorio?

- `hopping_hoop_simulacion.ipynb`: Cuaderno Jupyter compatible con Google Colab para correr la simulación.
- Posibilidad de subir archivos `.trk` (opcional, desde Tracker Video Analysis).
- Simulación sin gráficos, orientada a análisis numérico y toma de decisiones rápidas.
- Interfaz de entrada sencilla con `input()`.

---

## ✅ ¿Cómo usarlo?

### En Google Colab

1. [Abre este enlace en Google Colab](https://colab.research.google.com/) o sube el `.ipynb`.
2. Ejecutá las celdas una por una.
3. Cuando te pida, **ingresá la masa extra en kilogramos** (por ejemplo: `0.066`).
4. El sistema te dirá si hay **0, 1, 2 o 3 saltos**.

### En Jupyter Notebook local

```bash
git clone https://github.com/tuusuario/hopping-hoop-simulacion.git
cd hopping-hoop-simulacion
jupyter notebook hopping_hoop_simulacion.ipynb
