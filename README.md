# Analisis predictivo para una tienda minorista
### Objetivo:
Desarrollar un **modelo predictivo** para una **tienda minorista** que desea pronosticar las ventas basandose en diversas caracteristicas. La tienda ha estado recopilando datos sobre las ventas diarias y quiere utilizar esta información para tomar decisiones informadas sobre la *gestión de inventario*, *promociones* y *programación de personal*.
Por esto creamos un modelo que pueda **predecir el total de ventas para el proximo mes**, utilizando los datos de los meses anteriores.

### TAREAS:
**1. Preparacion de Datos**
Cargamos el conjunto de datos y realizamos el preprocesamiento necesario, como manejar **valores faltantes**, selección de **variables dependientes e independientes**, y dividir los datos en **conjuntos de entrenamiento** y **prueba**.

**2. Analisis Exploratorio de Datos (EDA)**
Realizamos un EDA para entender la distribución de las ventas y la relación entre las ventas y otras características. Esto podría incluir trazar las ventas a lo largo del tiempo, analizar las ventas en *festivos* vs. *no festivos* y el impacto de las promociones.

**3. Seleccion del Modelo**
Utilizamos la **Regresión Lineal**, los **Árboles de Decisión** y los **Bosques Aleatorios**.

**4. Entrenamiento y Evaluación del Modelo**
Entrenamos tu modelo seleccionado en el conjunto de entrenamiento y evaluamos su rendimiento utilizando el conjunto de prueba. Utilizamos gráficos para visualizar las *ventas reales* vs. *ventas predichas*.

<img width="864" alt="Captura de pantalla 2024-08-25 a la(s) 9 14 13 a  m" src="https://github.com/user-attachments/assets/a0c54579-3e0d-402c-b9b8-4acfdafbdbaa">

En el grafico, se muestra un diagrama de dispersion en el cual se evidencia que el modelo de regresion lineal esta haciendo un buen trabajo al predecir las ventas. La linea de tendencia indica que existe una fuerte relacion positiva entre los valores reales y predichos, lo que indica que el modelo puede capturar la tendencia de las ventas con eficiencia.


