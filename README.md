
# Laboratorio: Desarrollo de Proyectos y Productos de Datos - Profesor: Alonso Astroza
Este repositorio corresponde a un proyecto desarrollado para el curso de Desarrollo de Proyectos y Producto de Datos del Magíster en Data Science, Universidad del Desarrollo. El proyecto toma como base el repositorio clase_productodatos_2019_udd de Alonso Astroza ([https://github.com/aastroza/clase_productodatos_2019_udd](https://github.com/aastroza/clase_productodatos_2019_udd)), y se adaptó para hacer un detector de incendios forestales.

## Propuesta: Forest Fire Detection
La visión del proyecto Forest Fire Detection es generar una aplicación que recibe imágenes aéreas de bosques y detectar si se ha iniciado un incendio en esa zona. Para ello se entrenó un modelo de Deep Learning, en particular una red neuronal convolucional de arquitectura resnet43, con 400 imágenes aéreas de zonas con bosques: 200 con incendio y 200 sin incendio (puede ver los detalles en el [notebook](https://github.com/AndreaVerena/forest-fire-classification/blob/master/notebooks/clasificador-deteccion-incendio.ipynb)).

## ¿Cómo probar la app?
Para probar la aplicación, usted debe ingresar a la app en [https://forest-fire-classification.herokuapp.com](https://forest-fire-classification.herokuapp.com) y cargar una imagen aérea de bosques desde su equipo. Para obtener el resultado presione el botón "Predecir" y se mostrará el resultado:
- Fire: indica que se ha detectado un incendio forestal en la imagen analizada.
- No_Fire: indica que no se ha detectado un incendio forestal en la imagen analizada.


## Créditos

- La construcción del modelo está basada en las clases de [Francisco Ingham y Jeremy Howard](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb). La aplicacion web está inspirada en el trabajo de [Shankar Jha](https://github.com/shankarj67/Water-classifier-fastai).



