# Evaluación de Datos y Análisis de Resultados
***
Introducción

En esta evaluación, trabajaremos con dos conjuntos de datos proporcionados por el Ayuntamiento de Barcelona. El primer conjunto de  [datos](https://opendata-ajuntament.barcelona.cat/data/es/dataset/est-mercat-immobiliari-lloguer-mitja-mensual/resource/0a71a12d-55fa-4a76-b816-4ee55f84d327) es las Estadísticas del Mercado Inmobiliario - Alquiler Promedio Mensual, que contiene información sobre los precios de alquiler mensual promedio en Barcelona . El segundo conjunto de [datos](https://opendata-ajuntament.barcelona.cat/data/es/dataset/poblacio-exposada-mapa-estrategic-soroll/resource/3846500e-72aa-4780-967f-f09aa184eaba)  es la Población Expuesta al Ruido del Mapa Estratégico de Ruido, que proporciona datos sobre la población expuesta al ruido en diferentes zonas de la ciudad.

### Limpieza de Datos
En esta sección, describiremos las técnicas de preprocesamiento de datos que hemos aplicado a los dos conjuntos de datos. Los datos pueden contener errores, valores faltantes y otros problemas que deben abordarse.
### Conjunto de Datos del Mercado Inmobiliario
1. **Limpieza de Datos**: He revisado los datos para identificar y eliminar valores nulos, duplicados y posibles errores en los datos de precios de alquiler.


### Conjunto de Datos de Población Expuesta al Ruido
1. **Limpieza de Datos**: He revisado los datos para identificar y eliminar valores nulos, duplicados y posibles errores en los datos del ruido.
2. **Estandarización/Normalización:** he normalizado las variables del dataset del Ruido para luego poder usar el PCA.

### Resultados

1. Al usar el PCA se ha podido reducir el numero de variables del dataset del ruido a 18 variables.
2. Se ha unido el dataset del ruido con el dataset del precio.
