# telecom-analysis
# 📊 Proyecto de Análisis de Clientes - ConnectaTel

## 📌 Objetivo del proyecto

El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel durante 2024 mediante técnicas de exploración, limpieza y visualización de datos.

Se busca identificar:
- patrones de uso,
- segmentos de clientes,
- diferencias entre planes,
- usuarios de alto consumo,
- oportunidades comerciales para mejorar la oferta de servicios.

---

## 🗂️ Datasets utilizados

El proyecto utiliza los siguientes archivos CSV:

### `users_latam.csv`
Contiene información de los usuarios:
- `user_id`
- `age`
- `city`
- `plan`
- `reg_date`

### `usage.csv`
Contiene registros de uso del servicio:
- `user_id`
- `type`
- `duration`
- `date`

### `plans.csv`
Información de los planes disponibles:
- nombre del plan
- características
- límites y costos

---

## 🔎 Etapas del análisis realizadas

### 1. Carga y exploración inicial
- Importación de librerías
- Lectura de datasets
- Revisión de estructura y tipos de datos

### 2. Limpieza de datos
- Conversión de fechas
- Revisión de valores nulos
- Validación de variables categóricas
- Detección de outliers

### 3. Ingeniería de variables
- Creación de métricas agregadas:
  - cantidad de mensajes
  - cantidad de llamadas
  - minutos de llamada
- Segmentación por:
  - nivel de uso
  - grupo de edad

### 4. Análisis exploratorio
- Resúmenes estadísticos
- Histogramas
- Boxplots
- Distribución por tipo de plan

### 5. Insights de negocio
- Identificación de clientes de alto valor
- Evaluación de patrones de consumo
- Recomendaciones comerciales

---

## ▶️ Cómo ejecutar el notebook

### Opción 1: Google Colab

1. Abrir Google Colab:
   https://colab.research.google.com/

2. Subir el archivo `.ipynb`

3. Subir los datasets CSV al entorno de trabajo

4. Ejecutar las celdas en orden

---

### Opción 2: Jupyter Notebook

Instalar dependencias:

```bash
pip install pandas numpy matplotlib seaborn
```

Abrir Jupyter Notebook:

```bash
jupyter notebook
```

Abrir el archivo `.ipynb` y ejecutar las celdas.

---

## 🔁 Guía de reproducción

1. Descargar los datasets
2. Colocar los archivos CSV en la carpeta `/datasets`
3. Ejecutar el notebook desde el inicio
4. Revisar las visualizaciones y conclusiones
5. Replicar o modificar los análisis según sea necesario

---

## 📈 Principales hallazgos

- Los usuarios Premium presentan mayores niveles de consumo.
- Existen usuarios con consumos extremos que representan oportunidades comerciales.
- La edad no influye significativamente en la elección del plan.
- Los planes actuales podrían optimizarse mediante segmentación de clientes.

---

## 🛠️ Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab
