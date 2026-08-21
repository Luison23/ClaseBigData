# ClaseBigData 📊

Repositorio creado como entrega de la **Tarea 14 – Repositorio de Código** de mi clase de especialidad en Ciencia de Datos / Big Data. Contiene los notebooks de Python trabajados a lo largo del curso, cubriendo desde análisis exploratorio y machine learning clásico hasta procesamiento de lenguaje natural (NLP), series de tiempo y deep learning.

## 📁 Contenido del repositorio

| Notebook | Tema | Descripción |
|---|---|---|
| `practica1_webscraping.ipynb` | Web Scraping | Extracción de datos desde la web con `requests` y `BeautifulSoup`, y estructuración de la información en un `DataFrame` de pandas. |
| `02-association-rule-mining-on-real-data.ipynb` | Reglas de Asociación | Minería de reglas de asociación (algoritmo Apriori) sobre datos reales usando `mlxtend`. |
| `Iris_LogisticRegression.ipynb` | Clasificación | Clasificación de especies del dataset **Iris** con Regresión Logística (`scikit-learn`), incluyendo matriz de confusión y métricas de evaluación. |
| `Housing_LinearRegression.ipynb` | Regresión | Predicción de precios de vivienda (dataset **California Housing**) usando Regresión Lineal, con evaluación mediante MSE y R². |
| `Decision_Tree.ipynb` | Clasificación | Construcción y visualización de un árbol de decisión (`DecisionTreeClassifier`), con reporte de clasificación y matriz de confusión. |
| `Tarea08_Clustering.ipynb` | Clustering | Ejercicios de clustering con **K-Means**, **Clustering Jerárquico** y **DBSCAN**, incluyendo cálculo de silhouette score. |
| `tf_idf.ipynb` | NLP | Representación de texto mediante **TF-IDF** con `scikit-learn` y análisis de polaridad con `TextBlob`. |
| `embeddings.ipynb` | NLP | Generación de representaciones vectoriales de palabras y documentos con **Word2Vec** y **Doc2Vec** (`gensim`). |
| `sentiment_analysis.ipynb` | NLP | Análisis de sentimientos de texto utilizando `nltk` y `TextBlob`. |
| `analisis_de_texto.ipynb` | NLP | Clasificación de encabezados de noticias (dataset **News Aggregator**, UCI) mediante un pipeline **Doc2Vec + SVM**. |
| `time_series.ipynb` | Series de Tiempo | Análisis y modelado de series de tiempo: descomposición estacional, prueba de estacionariedad (ADF), modelos **ARIMA**, **Prophet** y una red **LSTM** con TensorFlow/Keras. |
| `pytorch-mnist.ipynb` | Deep Learning | Reconocimiento de dígitos escritos a mano (dataset **MNIST**) con una red neuronal construida en **PyTorch**. |

## 🛠️ Tecnologías y librerías utilizadas

- **Manipulación de datos:** `pandas`, `numpy`
- **Visualización:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`, `mlxtend`
- **NLP:** `nltk`, `gensim`, `TextBlob`
- **Series de tiempo:** `statsmodels`, `prophet`
- **Deep Learning:** `PyTorch`, `TensorFlow / Keras`
- **Web Scraping:** `requests`, `BeautifulSoup`

## 🚀 Cómo usar este repositorio

1. Clona el repositorio:
   ```bash
   git clone https://github.com/<tu-usuario>/ClaseBigData.git
   cd ClaseBigData
   ```
2. Crea un entorno virtual e instala las dependencias que necesite cada notebook (revisa las celdas de importación de cada uno).
3. Abre los notebooks con Jupyter Notebook, JupyterLab o Google Colab:
   ```bash
   jupyter notebook
   ```

## 👤 Autor

Repositorio elaborado como parte de la asignatura de Big Data / Ciencia de Datos.

## 📄 Licencia

Uso académico. Libre de compartir con fines educativos.
