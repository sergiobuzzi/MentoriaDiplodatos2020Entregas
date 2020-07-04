# ___LINKS A REPOSITORIOS CON LAS ENTREGAS DE LOS GRUPOS 1 Y 2___

___Grupo 1___ https://github.com/Martin317/mentoria-prediccion-indices-financieros

___Grupo 2___ https://github.com/rengo/MentoriaDiploDatos








### MentoriaDiplodatos2020

## Repositorio de la mentoría: 

# Predicción Univariada y Multivariada de los Principales Índices Financieros del Mundo

El objetivo central de la mentoría es implementar modelos predictivos univariados y multivariados de series temporales convencionales y de aprendizaje automático (y combinaciones de ambos). Por medio de dichos modelos se intentará anticipar los movimientos de los los principales índices financieros del Mundo y si los mismos están interrelacionados. Si dicha relación no es muy estrecha, se encuentra soporte para proponer la diversificación internacional de los portafolios, o sea invertir un poco en cada mercado para reducir la exposición al riesgo. 

Uno de los desafíos mas interesantes de la mentoría consiste en que, al no ser demasido grande la cantidad de observaciones, cabe preguntarse qué tipo de algoritmo funcionará mejor. Por una parte, los modelos de aprendizaje profundo poseen la capacidad de capturar patrones complejos y no linealidades, pero alcanzan a desplegar toda su potencialidad en datasets grandes. Por la otra parte, los modelos estadísticos de series temporales no requieren tanta información pero presentan cierta dificultad para modelar no linealidades o quiebres estructurales. De esto surge la posibilidad de combinar ambos metodologías y probablemente de mejorar los resultados por medio de ingeniería de features y transformaciones basadas en el conocimiento del área específica.

¡Espero que te interese el desafío y aprendas mucho en el camino!

## Detalles

En el archivo [dataset.csv](https://github.com/sergiobuzzi/MentoriaDiplodatos2020/blob/master/dataset.csv) se proveen datos sobre los valores de cierre diario de 11 índices bursátiles (aproximadamente 19 años), y series de tipos de cambio para efectuar el análisis en una moneda común. Dicho dataset también contiene una serie de dolar "blue" para ajustar el tipo de cambio de Argentina en épocas de cepo cambiario.

Luego se presentan carpetas en las cuales se irán cargando los enunciados y soluciones de cada uno de los trabajos prácticos. A continuación se plantean los posibles contenidos generales a desarollar en los mismos:

#### TP1: Análisis y Visualización (29/6)

Exploración de la base de datos. Medidas de Estadística Descriptiva. Gráficos de evolución temporal. Identificación de outliers "comunes" vs. identificación de outliers temporales. Cálculo de correlaciones. Intuición básica del concepto de raíz unitaria.

#### TP2: Análisis y Curación de Datos (19/7)

Curación de la base de datos. Imputación de faltantes. Reconstrucción de serie de tipo de cambio de Argentina. Expresión de los índices en moneda común. Transformaciones de los datos.

#### TP3: Introducción al Machine Learning (16/8)

Separación de datos en entremamiento, validación y test. Aplicación de metodos simples de ML para regresión univariante. Selección de métrica. Selección de hiperparámetros. Comparación de resultados.

#### TP4: Aprendizaje Supervisado (13/9)

Estimación de modelos de serie temporales univariados y multivariados (ARMA y VAR). Estimación usando LSTM. Comparación. 

#### TP5: Aprendizaje No Supervisado (27/9)

Aplicacion de algoritmos de clustering de series de tiempo.

#### Presentación Final (6/11 - 7/11) 

Ideas: Combinación de modelos de la literatura específica de series temporales (ARMA - VAR - VECM) con LSTM. Presentación de los resultados de los prácticos.


