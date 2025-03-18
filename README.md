## Projeto de Reconhecimento de Dígitos com CNN

Este projeto utiliza o dataset Digit Recognizer do Kaggle para treinar uma Rede Neural Convolucional (CNN) capaz de reconhecer dígitos escritos à mão. Além de treinar o modeloe  realizar previsões, o projeto também inclui a visualização dos neurônios ativos durante o processo de previsão, fornecendo insights sobre como a CNN toma suas decisões.

## Passos do projeto: 

1. Pré-processamento dos dados:
   + carregamento dos dados de treino e teste.
   + normalização das imagens (escala de 0 a 1).
   + transformação dos rótulo em one-hot encoding.
  
2. Construção do modelo CNN:
   + definição da arquitetura da CNN com camadas convolucionais, pooling e fully connected.
   + compilação do modelo com otimizador Adam e função de perda categorical_crossentropy

     ![Captura de tela 2025-03-17 194734](https://github.com/user-attachments/assets/cea031db-bf78-4b97-8734-bd0081df2ee7)
  
3. Treinamento do modelo:
   + treinamento da CNN com os dados de treino.
   + validação do modelo com os dados de teste.
  
4. Realização de previsões:
   + uso do modelo treinado para prever dígitos a partir das imagens de teste.

5. Visualização dos Neurônios ativos:
   + extração das ativiações das camadas convolucionais durante a previsão.
   + visualização dos mapas de ativação para entender como a CNN reconhece os dígitos.

## Como executar o projeto

1. Clone o repositório

