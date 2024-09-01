# Procesamiento del Lenguaje Natural (NLP)
<img src="https://github.com/zeushg/Desafios_NLP/blob/main/logoFIUBA.jpg" width="500" align="center">

# Resumen
Repositorio que contiene los desafios planteados de la materia Procesamiento del Lenguaje Natural (NLP).

# 1. Vectorización de texto 🔧⚙️
(https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_1/Desafio_1.ipynb)

Se realiza vectorización de documentos y estimar la similaridad que hay entre ello ademas ver el modelo de clasificación Naïve Bayes con el dataset 20 newsgroups.

# 2. Preprocesamiento de texto y Word Embeddings 🔧⚙️
(https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_2/Desafio2.ipynb)

Utilizando Gensim se crean embeddings de palabras a partir de un corpus de texto. Se hace una exploracion de tecnicas de embedding, se hacen pruebas con terminos de interes y se verifican sus similaridades y ver su contexto, ademas de la grafica de los embedings

Graficos obtenidos: (https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_2/Graficos_NLP_embeddings.pdf)

texto analizado [Oscar Wilde - El Retrato de Dorian Gray](https://www.textos.info/oscar-wilde/el-retrato-de-dorian-gray/)



# 3. Modelo de lenguaje con tokenización de caracteres y palabras 🔧⚙️ 
(https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_3/Desafio3_modelo_lenguaje_char.ipynb y https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_3/Desafio3_modelo_lenguaje_word.ipynb)

Se define un modelo de lenguaje utilizando tokenización por palabras y caractéres 
Se busca durante el entrenamiento baje el indicador dee perplejidad
se explora el comportamiento de las arquitecturas y 3 arquitecturas: SimpleRNN, LSM y GRU

Graficos obtenidos Modelo Char: (https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_3/TP3_secuencias_Modelo_lenguaje_CHAR.pdf)
Graficos obtenidos Modelo Char: (https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_3/TP3_secuencias_Modelo_lenguaje_WORD.pdf)

Texto analizado [Oscar Wilde - El Retrato de Dorian Gray - Modelo Char](https://www.textos.info/oscar-wilde/el-retrato-de-dorian-gray/)
Texto analizado [Franz Kafka La Metamorfosis - Modelo Word](https://www.textos.info/franz-kafka/la-metamorfosis/)

# 4. Chatbot Q&A con LSTM 🔧⚙️
(https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_4/_Desafio_4_bot_qa.ipynb)

Se implementa un chatbot de preguntas y respuestas usando embeddings de palabras para este caso Fasttext  y redes LSTM se utiliza informacion del challenge ConvAI2
Se hace acondicionamiento de datos para limpiarlos, se tokenizan, se crea el dataset separando entrenamiento y validacion, se hace el entrenamiento usando LSTM.


# 5. Bert Sentiment Analysis 🔧⚙️ 
(https://github.com/zeushg/Desafios_NLP/blob/main/Desafio_5/Desafio5_7d_bert_sentiment_analysis_multicategorial.ipynb)

Se realiza un modelo de clasificación de Sentiment Analysis utilizando el modelo BERT como encoder, los datos provienen de las críticas de Google Apps
Modelo entrenado con 3 clases: Positivo, Neutral y Negativo esto fue obtenido a partir de 5 clases iniciales.
Se plantean 3 modelos con distintas clases y capas densas.


# Author ✒️
:octocat: Zeus Hernández 
Contacto zeushg@gmail.com 