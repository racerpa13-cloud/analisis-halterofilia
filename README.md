# Análisis de los Campeonatos Europeos de Halterofilia (2019-2024)

## 1. Descripción del proyecto

Este proyecto analiza los resultados de los Campeonatos Europeos de Halterofilia entre 2019 y 2024, con el objetivo de identificar patrones de rendimiento deportivo, distribución de medallas por país y diferencias entre atletas masculinos y femeninos.

El análisis parte de un caso de negocio planteado por Lift & Lead, una startup interesada en estudiar el mercado europeo para la posible apertura de centros especializados en halterofilia.

## 2. Objetivos

- Analizar la distribución de medallas de oro, plata y bronce por país.
- Estudiar el equilibrio de medallas entre atletas masculinos y femeninos.
- Comparar los promedios de peso total levantado por país y género.
- Identificar patrones y limitaciones relevantes para la interpretación de los resultados.

## 3. Metodología

El proyecto se desarrolla en dos fases:

**Fase 1. Análisis inicial (2019-2020)**

Carga de archivos CSV, exploración, transformación de datos, conversión de tipos y análisis exploratorio.

**Fase 2. Ampliación del análisis (2019-2024)**

Obtención de información adicional mediante web scraping de Wikipedia, integración de datasets, validación de inconsistencias y ampliación del análisis exploratorio.

Durante la preparación se identificaron y documentaron dos incidencias relevantes:

- **Duplicidad de campeonatos:** se excluyeron los registros de 2020 del análisis ampliado, al corresponder a la competición aplazada a 2021.
- **Inconsistencia en resultados deportivos:** se corrigió un resultado de Kamila Konotop (2022), contrastándolo con datos oficiales.

El análisis ampliado incluye cinco ediciones celebradas y un total de 300 registros de medallistas.

## 4. Principales resultados

- **Armenia** lidera el número total de medallas, con 44.
- **Bulgaria** obtiene el mayor número de medallas de oro, con 15.
- **Turquía** presenta una distribución proporcionalmente equilibrada de medallas entre géneros (57,14 % frente a 42,86 %), con un total de 28 medallas.
- **Rumania** registra la menor diferencia absoluta entre los promedios de peso levantado por género (36,79 kg), aunque la comparación está condicionada por el tamaño de las muestras y las categorías de peso.

## 5. Conclusiones y limitaciones

El análisis permite identificar países destacados, patrones de distribución de medallas y diferencias en los resultados deportivos.

Sin embargo, los datos corresponden exclusivamente a medallistas y no permiten evaluar directamente la popularidad de la halterofilia ni establecer una relación causal con el crecimiento del CrossFit.

Para analizar la viabilidad comercial de centros especializados sería necesario incorporar indicadores de participación deportiva, interés del público y demanda potencial.

## 6. Fuentes de datos

- [Wikipedia – Campeonato Europeo de Halterofilia](https://es.wikipedia.org/wiki/Campeonato_Europeo_de_Halterofilia)
- Federación Internacional de Halterofilia (IWF).
- Federación Europea de Halterofilia (EWF).
- Agencia Internacional de Controles (ITA).

Las fuentes oficiales se utilizan para contrastar las incidencias detectadas durante la preparación de los datos.
