# Parcial 2 — Inteligencia Artificial

## Contenido

| Archivo | Descripción |
| --- | --- |
| `Informe_Parcial2_IA.pdf` | Informe con la solución de los cinco puntos (parte A, implementación, resultados e interpretación) |
| `Parcial_2_IA.zip` | Código en Python de los cinco puntos y README de ejecución |

## Ejecución

```bash
pip install matplotlib numpy
python punto1_genetico.py          # Algoritmo genético
python punto2_ascenso_colinas.py   # Ascenso de colinas
python punto3_temple_simulado.py   # Temple simulado
python punto4_aco.py               # ACO
python punto5_pso.py               # PSO
```

Cada archivo verifica con `assert` los cálculos de la parte A, ejecuta la parte B con semilla 42 y guarda la gráfica (`.pdf`) y el historial (`.csv`) en la carpeta `resultados/`.
