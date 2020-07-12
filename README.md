# Taller 2 de Introducción a Redes neuronales.



## Sitios de interes

- [Lo básico sobre optimizadores](https://medium.com/datadriveninvestor/overview-of-different-optimizers-for-neural-networks-e0ed119440c3)
- [Algunos optimizadores](https://medium.com/@sdoshi579/optimizers-for-training-neural-network-59450d71caf6)
- [Comparativa optimizadores](https://heartbeat.fritz.ai/an-empirical-comparison-of-optimizers-for-machine-learning-models-b86f29957050)
- [Notebook parte 1](https://colab.research.google.com/drive/1OiFikxiTOVNsf67OYnEhbfww4IcO79MY?usp=sharing)

## Respecto a la parte 2 del taller:

- [Modelo del Grafo](https://colab.research.google.com/drive/1MMBkT47tnMajMU2YflPXk16_x6mX-Tzk?usp=sharing)
- [Modelo Transformado](https://www.kaggle.com/ericzepeda/taller-2)



- Se transformó el grafo en un arreglo de 2 dimensiones tal que los espacios vacios (de haber) se rellenan con ceros. Este consiste en 

<img src="https://render.githubusercontent.com/render/math?math=(A\cdot \sum_{i=1}^{i=n} B_{i},6)">

Donde A corresponde al total de grafos que se tiene y <img src="https://render.githubusercontent.com/render/math?math=B_{i}"> El largo del grafo i
 
- En el Dataframe df_relations se hace distinción entre Padre e hijo en cuanto a jerarquia del grafo. Es por ello que se antepone una letra P o C (correspondiente a pade e hijo respectivamente), para identificar las siguientes caracteristicas 'uid': 

- Identificador único del usuario en la bse de datos de twitter.
- 'tweet ID': Identificador del twitter.
- 'post time delay (in minutes)': Tiempo transcurrido del twitter en minutos

Note que no se pierde la estructura y de requerirse una limpieza de datos para mejorar la pureza habria que filtrar con pandas aquellos valores de id que sean 0 nomas.

- [Modelo NLP (Base)](https://colab.research.google.com/drive/1xKDPHg7ek-WPPgZfkMXvP3Y_gcH3FKI_?usp=sharing)
-[Modelo NLP (NNLM)](https://colab.research.google.com/drive/1ynhsfazGUgSVk2lbTsGg6qqkPBMy8cxM?usp=sharing)
