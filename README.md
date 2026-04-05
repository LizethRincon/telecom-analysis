# Telecom Analysis – Sprint 7
Este repositorio contiene el análisis realizado durante el Sprint 7 del caso de una empresa de telecomunicaciones en Latinoamérica, ConnectaTel.

El dataset `plans.csv` incluye información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
El dataset `users.csv` incluye información de los clientes (edad, ciudad, fecha de registro, plan, churn)
El dataset `usage.csv` incluye detalle del uso real de los servicios (llamadas y mensajes)
El dataset `user_profile.csv` es una tabla agregadas por usuario que incluye métricas como (cantidad de llamadas, cantidad de mensajes, minutos, edad, plan. Este dataset se utiliza para segmentación de clientes y análisis de comportamiento.

## 📂 Contenido del repositorio
- `S7 Version-Estudiante-Project-ConnectaTel.ipynb`

## 🧠 Objetivo del análisis
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel (una empresa de telecounicaciones en Latam) a partir de su información demográfica y su uso de servicios (llamadas y mensajes), con el fin de identificar segmentos de clientes, patrones de consumo, posibles problemas en los datos y generar recomendaciones para la mejora de los planes telefónicos y la estrategia comercial.

El análisis busca responder preguntas de negocio como:
- ¿Qué tipos de clientes tiene ConnectaTel?
- ¿Cómo se comportan según su edad y nivel de uso?
- ¿Existen patrones de uso extremos?
- ¿Qué mejoras se pueden hacer a los planes actuales?

## Etapas del análisis
El proyecto se desarrolló siguiendo un flujo típico de análisis de datos:
1. Exploración de datos
- Revisión de estructura de los datasets
- Tipos de datos
- Valores faltantes
- Conversión de fechas
- Revisión de consistencia
  
2. Limpieza y preparación de datos
- Tratamiento de valores nulos
- Conversión de variables a tipo fecha
- Eliminación o análisis de valores atípicos
- Creación de métricas agregadas por usuario
- Unión de datasets
  
3. Análisis exploratorio
- Distribución de edades
- Distribución de llamadas, mensajes y minutos
- Comparación por tipo de plan
- Histogramas y boxplots
- Identificación de outliers
  
4. Segmentación de clientes
Se segmentaron los clientes según su nivel de uso:
- Usuarios de uso bajo
- Usuarios de uso medio
- Usuarios de uso alto

5. Insights de negocio
Se identificaron:
- Segmentos más valiosos
- Usuarios con riesgo de churn
- Patrones de uso extremos
- Recomendaciones de nuevos planes

## ▶ Cómo abrir el notebook en Google Colab
Haz clic en el siguiente botón:

[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg](https://github.com/LizethRincon/telecom-analysis/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb))](URL_DEL_NOTEBOOK_EN_GITHUB)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)
