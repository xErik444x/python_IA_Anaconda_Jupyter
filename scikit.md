Scikit Learn tiene algoritmos pre-construidos.

Importar el modelo (estimador). 
Por ejemplo: 
from sklearn.linear_model import LinearRegression 

Inicializar los parametros del modelo. Por ejemplo:
modelo = LinearRegression(normalize=True)
Los datos disponibles se dividen en datos de entrenamiento y datos de prueba (train_test_split)

Entrenar el modelo con los datos de entrenamiento. Por ejemplo: 
modelo.fit(X_train, y_train) Predecir las etiquetas o valores para los datos.

Por ejemplo:
predicciones = modelo.predict(X_test)
Ahora podemos evaluar nuestro modelo, comparando nuestras predicciones con los valores correctos de los datos de prueba 