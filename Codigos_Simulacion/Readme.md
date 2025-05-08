# 🌀 Calculadora del Salto del Aro Desbalanceado

Este cuaderno Jupyter (`.ipynb`) permite simular el comportamiento de un aro con una masa desbalanceadora adherida, y determinar si el sistema puede saltar en función de sus parámetros físicos.

---

## 📚 ¿Qué puedes hacer con este cuaderno?

✅ Verificar si el aro puede saltar  
✅ Calcular cuántas veces saltaría en un intervalo de tiempo  
✅ Estimar la altura máxima del salto  
✅ Visualizar una gráfica del movimiento vertical con los saltos  
✅ Modificar fácilmente los valores para nuevos experimentos

---

## 🧠 ¿Cómo se basa el modelo?

El cuaderno usa la condición:

\[
F_c = m \cdot \omega^2 \cdot r \geq (M + m) \cdot g
\]

para determinar si la fuerza centrífuga de la masa desbalanceadora es suficiente para levantar el aro del suelo.

---

## ▶️ ¿Cómo abrirlo en Google Colab?

Haz clic en el siguiente botón para abrirlo directamente:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amyaleja05/Trabajo_Reto_Cientifico/blob/main/Codigos_Simulacion/calculadora_saltos_avanzada.ipynb)

> 🔁 Reemplaza `USUARIO/REPO/ruta/archivo.ipynb` por la ruta real en tu repositorio.

---

## 📥 Cómo usarlo localmente

Si prefieres ejecutarlo en tu máquina local:

1. Asegúrate de tener `Jupyter` y `matplotlib` instalados:
   ```bash
   pip install notebook matplotlib
