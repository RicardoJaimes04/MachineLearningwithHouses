

**Modelos de Inteligencia Artificial para la Selección y Predicción de Vivienda*

<img src="https://github.com/RicardoJaimes04/MachineLearningwithHouses/blob/main/banner.png">

**Autores:** Yeison Adrian Caceres Torres, Ricardo Svensson Jaimes Estupiñan, Darien Andres Castañeda Agudelos

**Objetivo:** Predecir el precio de una vivienda en Colombia, dadas unas características. Ayudar a seleccionar vivienda a el usuario.

**Dataset:** 
Para la realización del proyecto se utilizó el dataset <a href="https://www.kaggle.com/datasets/rmjacobsen/property-listings-for-5-south-american-countries?select=co_properties.csv">Property Listings for 5 South American Countries</a>. Del mismo, seleccionamos únicamente el csv correspondiente a datos de propiedades en Colombia.

Los conjuntos de datos se originan de Properati Data, que es una división de datos de Properati, el sitio de búsqueda de propiedades de América Latina. En su <a href="https://www.properati.com.ar">sitio web</a> puede encontrar enlaces a diferentes herramientas y conjuntos de datos para utilizar libremente en sus proyectos. Todo lo que tienes que hacer es asegurarte de acreditarles los datos.

El dataset originalmente cuenta con:
- 25 columnas de datos
- 970.078 registros

**Problemática:**
En las últimas generaciones, la adquisición de vivienda propia se ha convertido en un desafío significativo debido al aumento constante de los precios. Por ejemplo, en Colombia, los precios de las propiedades han mostrado un incremento sostenido durante la última década, según cifras del DANE y otras entidades gubernamentales. Esto ha llevado a que, cuando surge la oportunidad de invertir en vivienda, las personas busquen cuidadosamente la mejor opción para maximizar el valor de su inversión.

Conscientes de esta problemática, nuestro proyecto busca aplicar los modelos de Machine Learning estudiados en la materia de Inteligencia Artificial para abordar el problema de encontrar vivienda de manera más eficiente. Este enfoque tiene como objetivo facilitar la toma de decisiones informadas al analizar grandes volúmenes de datos y predecir resultados relevantes.

## **Enfoques de Aplicación**

### **1. Modelos de Clasificación**
Este enfoque se centra en categorizar propiedades según diferentes criterios del dataset, intentamos predecir qué tipo de propiedad podría ser. Implementamos los siguientes modelos:

- **Gaussian Naive Bayes**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Classifier**
- **Redes Neuronales**

### **2. Modelos de Regresión**
El objetivo de este enfoque es predecir el precio de la vivienda a partir de ciertas características. Los modelos seleccionados incluyen:
- **Linear Regressor**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Support Vector Regressor**
- **Redes Neuronales**

### **3. Algoritmos Genéticos**
Se propone implementar un **algoritmo genético** para abordar problemas de optimización, en nuestro caso, encontrar la mejor combinación de propiedades dentro de un presupuesto específico o en función de múltiples restricciones (ubicación, superficie, número de habitaciones, entre otros).

Este proyecto busca no solo abordar una problemática social relevante, sino también explorar el potencial de la Inteligencia Artificial como herramienta para tomar decisiones más informadas en un mercado tan complejo como el inmobiliario.

---

## **Estructura del Proyecto**
El proyecto se desarrollará en las siguientes fases:
1. [**Análisis y normalización del dataset**](#analisis)
  - [**Visualización de datos**](#vis)
  - [**Limpieza y normalización del dataset**](#clean)
2. [**Implementación de los algoritmos de clasificación vistos en clase**](#cla)
3. [**Implementación de los algoritmos de regresión vistos en clase**](#reg)
4. [**Implementación de Algoritmos Genéticos**](#gen)

---

Explicación del Proyecto
Para una explicación detallada del proyecto, puedes ver el siguiente video en YouTube:{https://youtu.be/H6GAvFi5fRU}
