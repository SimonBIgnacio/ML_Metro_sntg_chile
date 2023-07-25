# Modelo Ml del metro Santiago de chile 
 El data set proviene del Instituto nacional de estadística de chile (INE).
 Esta información entrega la cantidad de usuarios que usan el metro a nivel mensual desde el año 2010 a la actualidad.
 Esta divido en uso total de pasajeros y sus derivados como escolares, gratuitos y pasajeros comunes donde todos esos suman el total de pasajeros que ocupan el metro.

# Objetivos
 Este proyecto tiene como objetivo realizar predicciones utilizando un modelo de ML. Sin embargo, es importante tener en cuenta dos acontecimientos significativos que afectaron el conjunto de datos en términos de estacionalidad y tendencia. Estos eventos son:

1. Estallido Social - Octubre de 2019: Durante el mes de octubre del año 2019, se produjo un importante estallido social que tuvo un impacto significativo en los datos. Para asegurarnos de que nuestro modelo predice de forma adecuada en escenarios posteriores a este evento, hemos decidido limitar el estudio del proyecto hasta el año 2019, cuando las condiciones eran más estables.

2. Pandemia del COVID-19 - Marzo de 2020: La pandemia del COVID-19 comenzó en marzo de 2020 y tuvo un efecto masivo en prácticamente todas las áreas de la sociedad, incluidos los datos recopilados en este proyecto. Dado que nuestra intención es utilizar el modelo para predecir situaciones libres de COVID y posteriores al estallido social, excluiremos los datos posteriores a marzo de 2020.

Con estas consideraciones históricas, nuestro objetivo es asegurarnos de que el modelo sea lo más preciso posible al realizar predicciones en situaciones normales anteriores a la pandemia y el estallido social. Al limitar los datos a esta ventana temporal específica, podremos evaluar con mayor confianza la eficacia del modelo para su uso actual.

# Intrucciones 

 Este repositorio contiene dos archivos importantes para el proyecto:

Archivo.ipynb: En este archivo se encuentran los códigos y las conclusiones de cada análisis exploratorio y los modelos de Machine Learning utilizados en el proyecto. El análisis exploratorio incluye visualizaciones y estadísticas descriptivas para comprender mejor los datos. Los modelos de Machine Learning se han implementado para realizar predicciones y generar resultados relevantes. Los comentarios y explicaciones dentro del archivo.ipynb guiarán a los usuarios a través del proceso y de los resultados obtenidos.

datos_estudio.csv: Este archivo contiene los datos que han sido utilizados para llevar a cabo el análisis y entrenar los modelos de Machine Learning. Los datos se presentan en formato Excel y están organizados en columnas significativas para el proyecto. Es importante asegurarse de que este archivo esté disponible para que el código del archivo.ipynb pueda acceder y procesar los datos correctamente.

Por favor, siéntase libre de explorar el repositorio, revisar el código y las conclusiones, y utilizar los datos para cualquier propósito de investigación o estudio. Cualquier comentario, sugerencia o contribución adicional será bienvenida y puede enviarse a través de los problemas o solicitudes de extracción en GitHub.


Github tiene problemas para leer la biblioteca Plotly. Recomendamos descargar el ipynb para ver los graficos
 
  


 
