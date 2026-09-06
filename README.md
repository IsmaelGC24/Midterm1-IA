# Midterm 1 - Inteligencia Artificial

Examen práctico: **Q-Learning con Pac-Man**.

## Contenido

El notebook `04_qlearning_pacman_examen.ipynb` implementa:

1. Inicialización de la Q-table
2. Política ε-greedy (`choose_action`)
3. Actualización de Q-Learning (`update_q`)
4. Ciclo de entrenamiento (`train_q_learning`)
5. Curva de aprendizaje (recompensa promedio y tasa de victoria)
6. Interpretación de los Q-values del estado inicial
7. Comparación entre política aleatoria y política aprendida

## Cómo ejecutarlo

1. Instalar dependencias:
   ```bash
   pip install numpy matplotlib ipython
   ```
2. Abrir `04_qlearning_pacman_examen.ipynb` en Jupyter o VS Code.
3. Ejecutar las celdas en orden. `src/tabular_pacman_env.py` debe estar en la carpeta `src/` junto al notebook.