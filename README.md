🛡️ Machine Learning & Protección de Datos: Compañía de Seguros "Sure Tomorrow"
Este proyecto desarrolla un modelo de Machine Learning para la compañía de seguros Sure Tomorrow, con un doble objetivo: resolver tareas específicas de negocio (predicción de beneficios y clasificación) y garantizar la privacidad de los datos de los clientes mediante técnicas de ofuscación matemática.

📋 Objetivos del Proyecto
Segmentación de Clientes: Encontrar clientes similares a un perfil determinado para optimizar estrategias de marketing.

Predicción de Beneficios: Determinar la probabilidad de que un nuevo cliente reciba una prestación del seguro.

Regresión Lineal: Predecir la cantidad de prestaciones de seguro que un nuevo cliente podría recibir.

Ofuscación de Datos: Implementar un algoritmo de transformación de datos que proteja la información personal sin sacrificar el rendimiento del modelo.

🛠️ Stack Tecnológico
Lenguaje: Python 3.x

Librerías principales: * Pandas & NumPy (Procesamiento de datos)

Scikit-learn (Modelado y métricas)

Matplotlib & Seaborn (Visualización)

Algoritmos: KNN (Vecinos más cercanos), Regresión Lineal, Métricas de distancia (Euclidiana, Manhattan).

🔐 Protección de Datos (Ofuscación)
Para cumplir con las normativas de privacidad, se implementó una técnica de enmascaramiento mediante una matriz invertible P.

D 
new
​	
 =D×P
Donde:

D es la matriz de datos originales.

P es una matriz aleatoria invertible.

Resultado: Los datos se vuelven irreconocibles para el ojo humano, pero las distancias y relaciones matemáticas se mantienen constantes, permitiendo que el modelo de ML funcione con la misma precisión (R 
2
  idéntico).

📊 Resultados Obtenidos
Clasificación: Se logró un modelo capaz de predecir la elegibilidad de beneficios con un F1-score superior al 0.90.

Regresión: Se comparó el desempeño con y sin ofuscación, demostrando que el error cuadrático medio (MSE) se mantiene inalterado tras la transformación.

Similitud: La implementación de KNN permitió identificar perfiles de clientes específicos con una precisión del 100% en casos de prueba controlados.

🚀 Cómo utilizar este repositorio
Clona el repositorio:

Bash
git clone https://github.com/iqmancilla-ARI/G_14.git
Instala las dependencias:

Bash
pip install -r requirements.txt
Ejecuta el Jupyter Notebook Sprint_14_G_14.ipynb para ver el análisis completo.

Desarrollado por: Daniel Mancilla

Senior Operations Executive | Data Science Enthusiast
