# Avaliação de técnicas de Data Augmentation para CNN no reconhecimento de raças de cachorro por meio de imagens

**Trabalho 2 da Disciplina de Aprendizado de Máquina 2**

**Professor: Diego Furtado Silva**

Integrantes:

- Lucas Vinícius Domingues 769699
- Rafael Yoshio Yamawaki Murata 769681
- Victor Luís Aguilar Antunes 769734



## Link para o Dataset: ##

- [Dog Breed Classification](https://www.kaggle.com/datasets/abhinavkrjha/dog-breed-classification?resource=download): Dataset para classificação de raças de cachorros a partir de imagem

**ATENÇÃO:** O dataset é muito grande para que seja realizado o Upload neste repositório, dessa forma deve-se **realizar o download no link disponibilizado** e **renomear a pasta dentro do zip como "dogs"**

> Foram utilizadas Redes Neurais Convolucionais para a realização da tarefa, mais especificamente com o uso de Transfer Learning da arquitetura VGG19, onde foram treinadas as duas últimas camadas convolucionais e adicionadas camadas densas.

> O uso de Data Augmentation com a biblioteca imgaug colaborou para o aumento moderado de 64% para 68% na acurácia para o conjunto de teste, sendo dobrado o tamanho do dataset original
