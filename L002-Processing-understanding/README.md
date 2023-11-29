# 2. Procesamiento y comprensión de documentos de requisitos

## Objetivo

* Que el alumno aplique los conceptos básicos de procesamiento de textos a tareas propias del análisis de documentos de IR

## Contenido

1. Análisis de textos
2. Componentes léxicos
3. Normalización de texto
4. Sintaxis y estructura de documentos de requisitos de SW

* [Análisis de textos](#análisis-de-textos)
    * [Tokenización](#tokenización)
    * [Normalización](#normalización)

## Análisis de textos

Las algoritmos de aprendizaje automático (ML por sus siglas en inglés de Machine Learning) trabajan con características de entrada de tipo numérico. 

El uso de proprocesamiento de texto o pre-procesamiento implica utilizar un conjunto de técnicas para convertir texto en una secuencia de componentes lingüísticos bien definidos que tengan tanto una estructura y notación estandarizada.

Las técnicas más comunes de pre-procesamiento de texto son:

* Tokenización
* Etiquetado
* Chunking
* Stemming
* Lematización

Adicionalmente, es necesario aplicar algunas otras operaciones básicas como la corrección de texto mal escrito, remover palabras vacías, y manejo de elementos irrelevantes de acuerdo al problema a resolver.

Contar con un sistema de pre-procesamiento de texto robusto es básico para cualqueir aplicación de NLP y análisis de textos, como es el caso del anális de textos para la ingeniería de requisitos.

### Tokenización

Los tokens son componentes textuales independientes y mínimos que tienen alguna sintaxis o semántica definida.

La tokenización puede ser definida como el proceso de separa datos textuales en pequeños componentes con significado llamados tokens.

#### Tokenización de oraciones

La **tokenización de oraciones** es el proceso de separar un [[corpus de texto]] en sentencias que actúan como el primer nivel de tokens que componen el corpus. 

Existen varias formas de realizar la tokenización de sentencias. Las técnicas básicas incluyen buscar delimitares específicos entre sentencias, como el punto y aparte (**.**) o un caracter de nueva linea (\n), y algunos otras veces punto y coma (;). 

[Ejemplo 1. Tokenización de oraciones](./code/tokenization_nltk.ipynb)

#### Tokenización de palabras

La **tokenización de palabras** es el proceso de separar o sementar oraciones en las palabras que la conforman. Una oración es una colección de palabras, y con la tokenización se obtiene una lista de palabras a partir de la oración que pueden ser utilizadas para reconstruir la oración. 

La tokenización de palabras es importante en muchos procesos, especialmente en la limpieza y normalización de los textos donde operaciones como stemming o lematización se aplica sobre cada palabra basado en sus respectivos stems (raíces) o lemas. 

[Ejemplo 2. Tokenización de palabras](./code/tokenization_words.nltk.ipynb)


### Normalización

La normalización de texto se define como el proceso que consiste en una serie de pasos a seguir para argumentar, limpiar y estandarizar los datos textuales en una forma que pueda ser consumida com entrada por otro sistema de análisis de PLN o aplicación. Además de la tokenización existen otras técnicas que incluyen la limpieza de testo, conversión de mayúsculas o minúsculas, correcciones ortográficas, eliminación de ***stopwords*** y otros términos innecesarios, ***steamming*** y lematización. 

La normalización de datos también es frecuentemente llamada: ***text cleansing*** o ***wrangling***.

[Ejemplo 3. Normalización](./code/text_normalization.ipynb)

### Stemming

Los morfemas son las unidades más pequeñas e independientes en un lenguaje natural. Los morfemas consisten de unidades que son raíces y afijos. Los afijos son unidades como prefijos, sufijos, entre otras; las cuales son agregados a las raíces de las palabras para cambiar sus significado o crear una nueva palabra. Las palabras raíces son también conocidos como forma base de una palabra (*base form*), y se pueden crear nuevas palabras mediante la unión de afijos en un proceso llamado como flexión (proceso de formación de una palabra). La inversa de esto es obtener la forma base de la palabra desde su forma de flexión y esto es conocido como stemming. 

[Ejemplo 4. Stemming](./code/stemming.ipynb)

### Compresión del textos

Existene algunos conceptos de ML que deben ser estudiados para comprender las implementaciones realizada.

- Preparación de los datos
- Extracción de características
- Características
- Datos de entrenamiento
- Datos de prueba/validación
- Modelo
- Exactitud (accuracy)

#### POS Tagging

El etiquetado de las partes del discurso (Part os Speech tagging o POS tagging) son categorías léxicas específicas a las cuales las palabras son asignadas basado en su contexto sintáctico y rol (pronombre, verbos, adjetivo y adverbio). 

[Ejemplo 5. POS Tagging]()