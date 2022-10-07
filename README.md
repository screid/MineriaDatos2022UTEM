# MineriaDatos2022UTEM
Repositorio del ramo Mineria de Datos para UTEM

Pasos para el preprocesamiento:

1. Ver los datos y detectar anomalías de formato (aplicación de transformación de datos).

2. Detectar outliers.

3. Agrupamiento de categorías similares en los datos categóricos (para así eliminar la maldición de la dimensionalidad).

4. Limpieza de datos nulos. En el puedo:
	1. Eliminar columnas
	2. Eliminar filas
	3. Reemplazar valores (sólo es válido si existe un <= 10% de data faltante y si los datos distribuyen normal. Si se cumplen ambos criterios, se puede reemplazar por la media de los datos).
	
5. Binarización de los datos categóricos.