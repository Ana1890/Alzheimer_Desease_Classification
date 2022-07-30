# Estadificación de Alzheimer por medio de imágenes MRI utilizando redes neuronales

Proyecto desarrollado dentro del Programa de Investigación en Ingeniería Biomédica (eje Inteligencia Artificial aplicada en salud) organizado por la Universidad Tecnológica del Perú - IEEE Student Branch -  a Student Chapter of the IEEE Engineering in Medicine & Biology Society and a Student Chapter of the IEEE Robotics & Automation Society.

Descripción: Las imágenes fueron recolectadas desde varios sitios web. Son imágenes MRI de cerebro en su corte axial y en formato .jpg a través de las cuales se pretende predecir el grado de demencia que puede tener un adulto en un momento determinado: demencia leve, demencia moderada, no demencia, demencia muy leve. De esta manera se contribuye al diagnóstico temprano de Alzheimer. Los datos se pueden hallar en https://www.kaggle.com/tourist55/Alzheimers-dataset-4-class-of-images.

Se propone reutilizar un modelo híbrido que funcionó bien en trabajos de investigación relacionados, y agregar una función de pre-procesamiento de los datos de entrada que nos permita uniformizar los mismos con respecto a sus niveles de grises. De esta manera se podría aumentar el nivel de generalización a más imágenes independientemente de las diferentes formas de adquisición, de los errores que se pudieron cometer, etc. 

# Conclusiones:
El primer modelo propuesto se encuentra overfitteado, lo que produce una perfomance no reproducible. Una causa de esto puede ser el gran desbalanceo que se presenta entre las clases. A pesar de que hicimos uso de los pesos en la función de pérdida, el modelo aún sigue sin performar del todo bien. Esto imposibilita realizar una comparación del mismo en cuanto a la etapa de pre-procesamiento de las imágenes. Una mejora que se puede hacer es un oversampling o data augmentation sobre las clases minoritarias, para poder balancearlas respecto a las clases mayoritarias. 

# Grupo 4 - Integrantes:

* Ana Rusconi
* Karen Obispo



