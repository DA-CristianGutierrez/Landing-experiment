# Landing-experiment

landing_experiment
Este repositorio contiene el análisis del experimento entre dos versiones de una página en una empresa de ecommerce.

El dataset landing_experiment incluye 40.000 registros de usuarios únicos que se registraron en una de las dos versiones de la página.

## 📂 Contenido del repositorio

- `S9 Version_Student_Proyecto_Landing_Experiment`
  → Notebook principal con limpieza, aplicación de pruebas estadísticas, distribuciones-gráficos y conclusiones.
  
## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DA-CristianGutierrez/Landing-experiment/blob/main/S9%20Version_Student_Proyecto_Landing_Experiment.ipynb)

o:

1.Abre el archivo .ipynb en GitHub

2.Haz clic en Open in Colab

## 📘 Cómo reproducir el análisis

1.Abre `S9 Version_Student_Proyecto_Landing_Experiment`
2.Ejecuta las celdas en orden
3.El notebook carga automáticamente el dataset desde /data/ o desde un enlace público (según corresponda)

## Análisis pruebas A/B

En este proyecto aplique un experimento A/B en una pagina de inicio de una empresa de e-commerce. Apliqué varios métodos estadísticos buscando diferencias significativas y que variables pudieran tener mayor influencia. Comparé las tasas de conversión así como el monto total vendido entre ambas páginas con el fin de mejorar efectividad de compra. Finalmente identifiqué que fuente canaliza más usuarios aportando mayor número de usuarios y preferencia por alguno de los canales en cuestión.

## 🧠 Objetivo del análisis

Explorar, validar y analizar estadísticamente el experimento A/B para identificar diferencias significativas entre las páginas y traducir los resultados en recomendaciones para el negocio.

## 🛠️ Herramientas y analisis aplicado:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

análisis correlacional (exploratorio) no causal.


## Metodología

- Exploración de datos: Se exploraron los datos para revisar su calidad así como revisar la distribución de estos em variables categóricas clave.
- Verificación clave: Se verificó que los registros tuvieran un identificador único y sin duplicados con el fin de evitar errores en la aplicación de las pruebas estadísticas.
- Aplicación de pruebas estadísticas: Se aplicaron las pruebas que determinan diferencias clave; promedios entre versiones, canales, tipos de usuarios.
- Segmentaciones clave: Se presentaron visualizaciones por segmentos clave para complementar y confirmar el analisis. 


## Visualizaciones destacadas

1. Gráfico conversiones por canal: La visualización indica claramente la fuente de tráfico más y menos usada por los usuarios así como una visual de conversión para cada fuente. La tasa de conversión es proporcional en todos los canales, lo cual indica que el proceso de compra es de gran fluidez en cada canal.


<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/a0333f25-5af2-45c1-9fa8-371b8d2628b3" />


----------------------------------------------------------------------------------------------------------------------------------------


2. Gráfico conversiones por tipo de usuario: Se evidencia una conversión proporcional entre ambos tipos de usuario, sin embargo, representando diferencias significativas en el volumen de estos, lo cual arroja una clave en este segmento.

<img width="589" height="455" alt="image" src="https://github.com/user-attachments/assets/9163a4ea-d031-4e25-a06b-f49d8a014372" />


## Conclusiones y recomendaciones
- Prueba entre versiones A/B: La diferencia en la tasa de conversión entre ambas paginas es de aproximadamente 3 puntos porcentuales,  predominando en el grupo B la mayor tasa de conversión. Es necesario considerar si vale la pena invertir en cambios teniendo en cuenta el margen presentado
- Organic y ADS son las fuentes que más usuarios canalizan, sin embargo, la tasa de conversión es simétrica en todos las fuentes de trafico.
- Los usuarios nuevos generan mayor cantidad de conversiones, sin embargo, la tasa de conversión se mantiene simétrica entre ambos grupos.

Acciones recomendadas:

- Revisar la diferencia de limitaciones entre las versiones de la página A y la página B así como el proceso de compra el cual es más efecctivo en la página B.
- Revisar el stock de productos buscados por usuarios recurrentes donde haya mayor coincidencia para generar promociones o incluso entender que están buscando realmente para incrementar la probabilidad de compra.

