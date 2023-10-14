# Proyecto de TimeSeries Multivariante

En este proyecto se intentaba predecir las ventas mensuales del mes de octubre a partir del histórico de ventas.

La idea era predecir por 'unique_id', el identificador único de cada producto, su propia predicción mensual para ese mes.

Se generarán variables nuevas utilizando lags y medias móviles para poder predecir lo que pasará en el siguiente mes.

Para ello, el notebook se compone de:

1) Importación de librerías
2) Cargar datos
3) EDA de diferentes parámetros que nos ayudarán a ver como es el problema que tenemos que resolver, insights de negocio interesantes y poder ver donde el modelo puede predecir mejor o peor.
4) Crear una función iterativa para poder hacer muchas pruebas y buscar el mejor modelo.
5) Instanciar y entrenar el modelo, utilizando un XGBoost Regressor
6) Evaluamos el modelo mediante la métrica RMSE. Hemos conseguido un modelo con RMSE de 2,78.
7) Realizamos diferentes comprobaciones más visuales para ver donde se puede estar equivocando nuestro modelo.
8) Finalmente se pasa a CSV para exportar y poder subirlo a una competición de Kaggle.


En definitiva, este notebook viene a representar un archivo completamente iterativo donde podemos hacer muchas pruebas de manera muy rápida, con el fin de buscar las mejores variables y parámetros para nuestro modelo. Y poder así, resolver nuestro problema de TimeSeries para múltiples ítems.


## Contiene el notebook de referencia utilizado y el CSV con los datos utilizados.