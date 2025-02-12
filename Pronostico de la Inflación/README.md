# Pronóstico de la Inflación en Bolivia para Año el 2025.

## Introducción

En este Proyecto se realiza el pronóstico de la inflación para Bolivia para el año 2025, aplicando la metodología de Box-Jenkins (1976), para identificar un modelo autorregresivo integrado de media móvil ARIMA(p,d,q).

Este método es muy popular para la previsión de series temporales dado que predice valores futuros combinando observaciones pasadas (AR), diferenciación para lograr estacionariedad (I) y errores pasados para afinar las predicciones (MA).

La información empleada es del Instituto Nacional de Estadística [(INE)](https://www.ine.gob.bo/). Para el pronóstico de la inflación se emplean datos de la variación a doce meses del índice de precio al consumidor desde 2015 hasta diciembre de 2024.

## Resultados

De acuerdo a los datos y la aplicación de la metodología de Box-Jenkins (1976):

+ El modelo ARIMA empleado es el ARIMA(3,1,1) corregido por la influencia de valores atípicos.

![Pron](https://github.com/DaM16/Portafolio/blob/e96660d64ac51a60fceaa2f56c1acc5251a54f9f/Pronostico%20de%20la%20Inflaci%C3%B3n/G1.png)

+ La inflación promedio pronosticada para el año 2025 será del 7.48%, 2.4 pp por encima del promedio registrado en 2024.

![Infl](https://github.com/DaM16/Portafolio/blob/e96660d64ac51a60fceaa2f56c1acc5251a54f9f/Pronostico%20de%20la%20Inflaci%C3%B3n/G2.png
)

* Además, de acuerdo con los datos, la inflación en el último semestre del año 2024 presentó una dispersión marcada, terminando el año con una inflación de 9.97%

Para mayores detalles el proyecto se encuentra alojado en [ R Pubs](https://rpubs.com/DaM16/1270934)




