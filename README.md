# VPC1-TP2
# Objetivo:
Implementar un detector de máximo enfoque sobre un video aplicando técnicas de análisis espectral similar al que utilizan las
cámaras digitales modernas. El video a procesar será: “focus_video.mov”.

# Parte 1: Se debe implementar un algoritmo que dada una imagen, o región, calcule la métrica propuesta en el paper 
"Image Sharpness Measure for Blurred Images in Frequency Domain“ y realizar tres experimentos:

Medición sobre todo el frame.

Medición sobre una ROI ubicada en el centro del frame. Area de la ROI = 5 o 10% del area total del frame.

# Opcional:
1. Medición sobre una matriz de enfoque compuesta por un arreglo de NxM elementos rectangulares equiespaciados. N y M son valores
arbitrarios, probar con varios valores 3x3, 7x5, etc … (al menos 3)
Para cada experimento se debe presentar :
- Una curva o varias curvas que muestren la evolución de la métrica frame a frame donde se vea claramente cuando el algoritmo detecto el punto
de máximo enfoque.

# Parte 2: _Analysis of focus measure operators in shape-from-focus_
Cambiar la métrica de enfoque eligiendo uno de los algoritmos explicados en el apéndice de: Analysis of focus measure
operators in shapefrom focus.
El algoritmo de detección a implementar debe detectar y devolver los puntos de máximo enfoque de manera
automática.
