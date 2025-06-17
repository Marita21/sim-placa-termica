# sim-placa-termica
# 🛰️ Simulación térmica de una placa en el espacio

Este script calcula la temperatura de equilibrio de una placa en el espacio usando un modelo simple de balance radiativo. Es una simulación básica útil como primer paso en estudios térmicos de subsistemas satelitales.

## 📋 Ecuación usada

Se aplica el balance entre energía absorbida y energía emitida:

\[
T = \left( \frac{\alpha \cdot q_{solar}}{\epsilon \cdot \sigma} \right)^{1/4}
\]

Donde:

- `α` es la absortividad de la superficie
- `ε` es la emisividad
- `q_solar` es el flujo solar incidente
- `σ` es la constante de Stefan-Boltzmann

## 📂 Archivos

- `sim_placa.py`: script en Python para ejecutar la simulación

## ▶️ Cómo ejecutar

```bash
python sim_placa.py
