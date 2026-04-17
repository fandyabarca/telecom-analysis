# telecom-analysis
## 📂 Contenido del repositorio
- `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
→ Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1F-tHmaNAFr7LN9zbuAhDFMHfrZaD3gOk?usp=sharing)


O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Mi objetivo fue evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.
- Trabajé con información registrada hasta el año 2024, lo cual me permitió analizar el comportamiento del negocio dentro de ese periodo.
Para ello trabajé con tres datasets:
- plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
- users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
- usage.csv → detalle del uso real de los servicios (llamadas y mensajes)
Exploré, limpié y analizé estos datos para construir un perfil estadístico de los clientes, detectar comportamientos atípicos y crear segmentos de clientes.
Este análisis me permitió identificar patrones de consumo, diseñar estrategias de retención y sugerir mejoras en los planes ofrecidos por la empresa.
