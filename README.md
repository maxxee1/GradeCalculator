
## Grade Calculator
Este proyecto utiliza técnicas de inteligencia artificial con la librería **scikit-learn** para realizar predicciones basadas en datos históricos. Con el fin de estimar cuántas horas de estudio se necesitan para alcanzar una calificación específica en un examen.

> [!WARNING]
> Las predicciones de este modelo no son 100% exactas, incluso con suficientes datos históricos. Factores externos o no considerados en este análisis pueden influir en los resultados finales.

### Descripción
El proyecto se basa en una relación sencilla de dos variables:  
1. **Horas de estudio:** Tiempo dedicado al estudio para cada evaluación.  
2. **Calificación obtenida:** Nota alcanzada en base al tiempo invertido.

> [!TIP]
> La **precisión del modelo** se puede ajustar según la cantidad y calidad de los datos históricos.  
> - Con pocos datos o de mala calidad con una alta dispersión, se ajusta la precisión a un valor como **0.8**.  
> - En caso de datos más consistentes, un valor de **0.95** es recomendable.  
> Todo esto puede configurarse fácilmente utilizando estructuras de control como `case` o `if-else` en Python.

A partir de los datos históricos registrados para cada asignatura/evaluacion, el modelo predice el tiempo necesario para alcanzar una calificación especifica utilizando regresión lineal.

> [!NOTE]
> Si deseas extender el proyecto para predecir con **más variables** (como datos extraídos desde un archivo CSV, incluyendo otros factores como métodos de estudio o asistencia a clases), deberás considerar el uso de algoritmos de agrupación o modelos de regresión más complejos.
