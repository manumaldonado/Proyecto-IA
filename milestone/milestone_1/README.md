# 🛠️ Primera Actividad del Proyecto

## Entregables de la Semana

### 1. **Nombre del equipo de proyecto**
<!-- markdownlint-disable MD036 -->
**The Debuggers**

### 2. **Integrantes del equipo:**

- **Adrián Sánchez**
- **Héctor Colmenares**  
- **Jorge Morales**  
- **Manuel Maldonado** (Líder del equipo)  

## Candidatos a proyectos

### 3.1 - SmartBudget AI | Predicción de Gastos y Análisis de Capacidad Crediticia

#### 3.2 - Breve descripción del proyecto

Con este candidato se busca usar los dataframes creados y procesados en el proyecto anterior, tomando en cuenta la información obtenida sobre el ingreso, gasto y calidad de vida de los jóvenes en Venezuela, datos que se obtuvieron mediante la encuesta de Google Forms y que juntaron un total de 123 filas de información. Con la finalidad de crear un modelo predictivo de los gastos mensuales y la capacidad crediticia de una persona (qué rango de crédito/préstamo podría solicitar sin caer en riesgo financiero), tomando en cuenta sus ingresos mensuales, su edad, su ocupación y el sector de trabajo en el que se encuentra.

En caso de que las 123 filas de datos no sean suficientes, se obtuvo un dataset con prácticamente las mismas columnas, de ingresos, gastos en transporte, alimentación, vivienda, entre otros. Con un total de 1000 filas, el cual también podría usarse para entrenar el modelo y mejorar su predicción.

#### 3.3 - Datasets

- [Student Spending Dataset](https://www.kaggle.com/datasets/sumanthnimmagadda/student-spending-dataset/data)
- [Global Income & Purchasing Power](https://www.kaggle.com/datasets/meeratif/global-income-purchasing-power)
- [Salarios en México](https://www.kaggle.com/datasets/emmanuelleai/salarios-en-mexico)
- [Morosidad Dataset](https://www.kaggle.com/datasets/luishcaldernb/morosidad)

---

### 4.1 - Dermatology AI | Clasificación y Segmentación de Lesiones Dermatológicas con Inteligencia Artificial 🤖👨‍💻👩‍💻🦾🔍👾

#### 4.2 - Descripción

Este proyecto tiene como objetivo crear una aplicación o plataforma web que utiliza inteligencia artificial (IA) para ayudar a identificar y analizar lesiones dermatológicas en la piel. Los usuarios podrán cargar imágenes de lesiones en la plataforma, y la IA se encargará de clasificarlas, indicando el tipo de lesión (como melanoma, queratosis, etc.). Se podría integrar un sistema de segmentación que ayudará a resaltar las áreas afectadas en la imagen, facilitando el diagnóstico.

**_Este proyecto será útil tanto para las personas que necesiten un diagnóstico preliminar como para dermatólogos que busquen una herramienta adicional para mejorar su trabajo._**

Las imágenes y los metadatos que provienen del ISIC archive se van usar así:

- **Imágenes:**
Las imágenes
descargadas de la API serán el insumo principal para
entrenar el modelo de clasificación y segmentación.
Cada imagen es etiquetada con información que ayudará al modelo a identificar patrones y características relevantes.

- **Metadatos:** Los metadatos asociados a cada imagen contienen información sobre la lesión (como el tipo de lesión, ubicación, diagnósticos, etc.), que serán importantes para etiquetar correctamente los datos durante el proceso de entrenamiento y validación del modelo. Permitirá realizar evaluaciones precisas de la efectividad del modelo cuando ya esté entrenado.

#### 4.3 - Datasets

- [ISIC Archive - Collection 390](https://api.isic-archive.com/collections/390/)
- [ISIC Archive - Collection 249](https://api.isic-archive.com/collections/249/)
- [ISIC Archive - Collection 67 (Page 2)](https://api.isic-archive.com/collections/67/?page=2)
- [Cancer Imaging Archive - CMB-MEL](https://www.cancerimagingarchive.net/collection/cmb-mel/)

**MVP (Producto Mínimo Viable):**

- Subida de imágenes de lesiones dermatológicas.
- Clasificación automática de las lesiones mediante IA.
- Segmentación de la lesión en la imagen.
- Visualización de la predicción junto con los resultados de segmentación.

---

### 5.1 - Proyecto de clasificación de imágenes médicas con IA

#### 5.2 - Descripción

Un proyecto de clasificación de imágenes médicas con IA consiste en enseñar a una computadora a identificar patrones en imágenes médicas como radiografías, para clasificarlas según diferentes categorías.

Esto sirve para diagnosticar más rápido y con más precisión, pues la IA puede detectar enfermedades como tumores y/o fracturas que a veces son difíciles de ver para el ojo humano. También puede identificar enfermedades en etapas iniciales, lo que permite tratamientos más efectivos.

Por ejemplo, se juntan muchas imágenes médicas ya clasificadas por médicos, luego la IA aprende a reconocer patrones en estas imágenes, relacionándolas con las diferentes categorías, una vez entrenada, el modelo puede clasificar nuevas imágenes médicas sin necesidad de intervención humana.

**Enlace del repositorio de GitHub:** [Proyecto IA](https://github.com/manumaldonado/Proyecto-IA)
