# T2---Predicting-Poverty
En este repositorio se busca hacer una predicción de pobreza en hogares en Colombia usando el dataset "Empalme de las Series de Empleo,
Pobreza y Desigualdad - MESE" del DANE. 
El repositorio contiene todos los archivos utilizados para realizar la predicción, junto con el informe en PDF que resume el proceso y los resultados.
# Archivos
En el Notebook "data_creator" contiene todos los modelos utilizados junto con todo el proceso de limpieza y adapatación de los datos. Este es de caracter autocontenido y posee celdas Markdownn donde se enuncia brevemente en que consiste la celda de código.

# Resultados.
En caso que el lector desee replicar los resultados obtenidos, le recomendamos acceder directamente a la sección de redes neuronales donde el último modelo corresponde al modelo que obtuvo el mejor rendimiento en la competencia. Para ello, es necesario que tenga acceso al conjunto de datos que posee el sitio oficial de la competencia: https://www.kaggle.com/competitions/uniandes-bdml-2024-20-ps-2/data

El mejor modelo obtuvo un puntaje preliminar en Kaggle de $F1_{score} = 0.676$.

# Modelo ganador

El modelo ganador corresponde a una red neuronal con la siguiente arquitectura:
![image](https://github.com/user-attachments/assets/fc722c9d-efe1-44b9-bd3b-992772eef261)



