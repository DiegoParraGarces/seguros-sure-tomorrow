# Machine learning y protección de datos en seguros

## Descripción

Proyecto para la aseguradora **Sure Tomorrow**: encontrar clientes similares, predecir prestaciones del seguro y proteger los datos personales sin perder calidad en los modelos.

## Resultados principales

- Busqué clientes similares con kNN, comparando distancias euclidiana y Manhattan, con y sin escalado.
- El clasificador kNN logró F1 de 0.61, frente a 0.20 del mejor modelo aleatorio.
- Implementé la regresión lineal desde cero con la ecuación normal.
- Oculté los datos multiplicándolos por una matriz invertible y demostré, analíticamente y con código, que las predicciones no cambian (RMSE 0.34 y R² 0.44 en ambos casos).

## Herramientas

Python, NumPy, pandas, scikit-learn, Seaborn

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
jupyter notebook 06_seguros_sure_tomorrow.ipynb
```

Los datos provienen del programa de formación en ciencia de datos y no se incluyen en este repositorio. El notebook se puede revisar con todas sus salidas directamente en GitHub.

## Autor

Diego Parra · [LinkedIn](https://www.linkedin.com/in/diegoparragar)
