# Aplicación de KNN (Vecinos más cercanos).


# Detección de fraude en tarjetas de crédito.


#### A medida que avanza la tecnología, también avanzan los delitos, los robos, las estafas, clonaciones de tarjetas, el fraude, etc. La realidad es que todos podemos ser víctimas de algunas de estas cosas. Por eso, el objetivo de este proyecto, es tratar de crear un buen modelo de predicción, que nos permita evitar o en otro caso proteger a algún usuario de estos tipos de fraude.


Para ello utilizaremos el algoritmo de aprendizaje supervisado KNN. Este se basa en instancias, es decir, que necesita datos para poder relacionarlos con aquellos existentes y así poder predecir correctamente o lo mejor posible.
Si bien se puede usar para la regresión, en esta ocasión lo utilizaremos para la clasificación.


El algoritmo es fácil de implementar. Sin embargo, como contra podemos decir que utiliza mucha memoria, ya que va punto por punto (o dato por dato), por lo que nos consumiría muchos recursos en la pc. Es un algoritmo que se recomienda utilizar en dataset que no contengan tantas variables ni tantos datos. En esta ocasión lo vamos a utilizar como práctica y aprendizaje.
Si bien el modelo KNN es el principal y vamos a profundizar un poco más, vamos a aplicar otros modelos de Machine Learning para compararlo con knn.

Los datos que manejamos están desbalanceados. Es decir, tenemos más cantidad de datos que no sufrieron fraude en nuestra variable dependiente o 'fraud'. Para solucionar eso, utilizaremos undersampling para abordar el desequilibrio de las clases. Para esto, vamos a usar la librería imblearn.under_sampling. 

# Datos que utilizaremos.


Los datos que vamos a usar los sacamos de https://www.kaggle.com/datasets.


Desde ya, muchas gracias por analizar el proyecto!!!
