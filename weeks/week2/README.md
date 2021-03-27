# Tools

Numpy, Pandas, Matplotlib, Keras, Tensorflow

* [Slides da Aula](https://docs.google.com/presentation/d/e/2PACX-1vQmTWR8lje4hd619-gXVBJbwytqmMK8fzH9kpgqnww9QB7KcsC1pE0dh3aZXK3t_wA_f_EVI4ebBr0G/pub?start=false&loop=false&delayms=3000)
* [Vídeo da Aula](https://www.youtube.com/playlist?list=PL-khHIKnEw7NoOjYO5b11A_LJQ0Ot804R)

# Assignments - PRAZO PARA ENTREGA: 9 de abril de 2021

[Video - Explicações Gerais](https://www.youtube.com/watch?v=Ug38GG3g28Q&list=PL-khHIKnEw7MFqHmeA5HFFQkPeRYTyi3_&index=1)

[Video - Como irei enviar meu trabalho ?](https://youtu.be/WZLP5J2YEAg) através do preenchimento do [formulário - ainda será adicionado....](), usando a conta de email da UFV.


Dúvidas: ricardo@ufv.br, michael.canesche@ufv.br

## Beginner

1. Modifique o [Laboratório do Exemplo DeepLizard](https://colab.research.google.com/drive/1OdD34nvfzGAUjWvIpUh3XPULJ2eeyQSS?usp=sharing#scrollTo=rM3fT8otpMDh) para executar com um conjunto de testes com 4200 participantes no lugar de 2100 participantes. O modelo da rede neural tem camadas com 16,32 e 2 neurônios. Modifique para 10,30 e 2. Quantos parametros tem sua rede agora ? Execute várias vezes o treinamento variando batch_size e epochs. Monte uma tabela da acurácia do treinamento e da validação fixando o batch_size em 20 e variando epoch em 5,10,15, 20 e 30. Agora fixar a epoch em 20 e variar o batch_size em 10,20,50 e 100. Enviar seu colab com o relatório no cabeçalho. Este laboratório está explicado com detalhes no [video do deeplizard](https://www.youtube.com/watch?v=qFJeN9V1ZsI&t=1393s)

## Intermediate

1. Modifique o [Laboratório do Exemplo DeepLizard](https://colab.research.google.com/drive/1OdD34nvfzGAUjWvIpUh3XPULJ2eeyQSS?usp=sharing#scrollTo=rM3fT8otpMDh) para parametrizar o tamanho do conjunto de testes e a percentagem de casos. Crie as variáveis Participants e SideEffectPercentage em uma célula inicial. Crie também nesta célula qual será a quantidade de neurônios para primeira e segunda camada: layer1 e layer2. No exemplo está com 16 e 32. Colocar também como parametro o tamanho do batch e o numero de epoch, nesta célula inicial. O [Laboratório CIFAR com uma rede 40 mil parametros](https://colab.research.google.com/drive/1078yR52_eyGdAVCVgtmKAlnJHBhfBl09?usp=sharing) mostra um exemplo para armazenar o histórico do *loss* e da acurácia durante o treinamento na seção **fitting**. Acrescente e modifique este código para plotar o gráfico do *loss* e da acurácia no seu exemplo do **DeepLizard**. 

## Advanced

1. Crie um novo laboratório para o Cifar10 que tem 4 opções de redes usando os modelos dos laboratórios 2,3,4 e 5 abaixo. O usuário poderá escolher o modelo, epoch, batch_size. O laboratório irá mostrar o gráfico de evolução da loss e da acurácia semelhante ao [Laboratório CIFAR com rede 110K paramêtros](https://colab.research.google.com/drive/1Aifzc6B7fIE5m7T731qFZzviIoGSDQQj?usp=sharing) como imprimir as imagens do conjunto de teste com label verde para certo e vermelho para errado. Deverá também imprimir o classification_report semelhante ao [Laboratório CIFAR com uma rede 40 mil parametros](https://colab.research.google.com/drive/1078yR52_eyGdAVCVgtmKAlnJHBhfBl09?usp=sharing).


# Laboratories

1.[Laboratório do Exemplo DeepLizard](https://colab.research.google.com/drive/1OdD34nvfzGAUjWvIpUh3XPULJ2eeyQSS?usp=sharing#scrollTo=rM3fT8otpMDh)
2.[Laboratório CIFAR com uma rede 40 mil parametros](https://colab.research.google.com/drive/1078yR52_eyGdAVCVgtmKAlnJHBhfBl09?usp=sharing)
3.[Laboratório CIFAR com uma rede 66 mil parametros]([Laboratório CIFAR com uma rede 40 mil parametros](https://colab.research.google.com/drive/1078yR52_eyGdAVCVgtmKAlnJHBhfBl09?usp=sharing)
4.[Laboratório CIFAR com rede 110K paramêtros](https://colab.research.google.com/drive/1Aifzc6B7fIE5m7T731qFZzviIoGSDQQj?usp=sharing). 
5. [Laboratório CIFAR com rede 1.6 milhões de paramêtros](https://colab.research.google.com/drive/11hDJ5NbBet9GyZHIHzD2HhYQdfBOVKnN?usp=sharing)


