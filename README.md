# Actividad 02: Algoritmos Genéticos en el Aprendizaje de Máquina

## Equipo de Trabajo
Este proyecto ha sido desarrollado de forma colaborativa por:
1. [Nombre de Persona 1] - Feature Selection
2. [Nombre de Persona 2] - Hyperparameter Optimization
3. [Nombre de Persona 3] - Neuroevolution
4. Yuri Florentino Quispe Hualla - Integración, Calidad y Entregables

---

## Objetivo
Comprender la aplicación práctica del ciclo completo de los algoritmos genéticos (representación de la población, inicialización, función de aptitud, selección, cruzamiento, mutación y terminación) aplicados a diferentes áreas del Machine Learning.

## Contenido del Repositorio
El proyecto se divide en tres implementaciones principales:

### 1. Feature Selection (Selección de Características)
* Dataset: Wine de scikit-learn (13 características).
* Modelo: Regresión Logística.
* Descripción: El algoritmo genético utiliza una representación binaria para encontrar el subconjunto óptimo de características que maximice el accuracy del modelo, penalizando ligeramente la cantidad de características para favorecer soluciones compactas.

### 2. Hyperparameter Optimization (Optimización de Hiperparámetros)
* Dataset: Breast Cancer Wisconsin de scikit-learn.
* Modelo: Random Forest Classifier.
* Descripción: Se emplea una representación mixta (entera y continua) para optimizar 6 hiperparámetros clave del modelo (n_estimators, max_depth, min_samples_split, min_samples_leaf, max_features, criterion). Se utiliza selección por torneo y mutación gaussiana/entera.

### 3. Neuroevolution (Pendiente de Integración)
* Descripción: Aplicación de algoritmos genéticos para hallar la mejor arquitectura de una red neuronal (capas, neuronas, funciones de activación).

---

## Tecnologías y Librerías Requeridas
El código está desarrollado en Python 3. Para ejecutar los cuadernos o el entorno gráfico integrado, se requieren las siguientes librerías:
* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn
* tkinter (Solo para la interfaz gráfica local, preinstalado en Python)

---

## Instrucciones de Ejecución

Existen dos maneras de evaluar y correr las implementaciones:

### Opción A: Ejecución en Google Colab / Jupyter Notebooks
1. Navega a la carpeta correspondiente dentro de este repositorio (/feature_selection, /hyperparameter_optimization, etc.).
2. Abre el archivo .ipynb correspondiente en Google Colab o en tu entorno de Jupyter local.
3. Ejecuta las celdas de forma secuencial. Las librerías necesarias ya están preinstaladas en el entorno de Colab.

### Opción B: Ejecución en Local con Interfaz Gráfica (Recomendado)
Para la sustentación oral, se ha creado un entorno unificado con interfaz gráfica (GUI) que permite la ejecución paso a paso.
1. Clona este repositorio en tu máquina local.
2. Abre el proyecto en un IDE como PyCharm o Visual Studio Code.
3. Instala las dependencias ejecutando: pip install numpy pandas matplotlib seaborn scikit-learn
4. Ejecuta el archivo integrador: python main.py
5. Selecciona el algoritmo deseado en el panel principal y utiliza el botón "Siguiente Paso" para avanzar en la ejecución.
