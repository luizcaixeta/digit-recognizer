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

     ![image](https://github.com/user-attachments/assets/a73f2762-1568-4bab-a4f3-6d1c02ff7c2f)

5. Visualização dos Neurônios ativos:
   + extração das ativiações das camadas convolucionais durante a previsão.
   + visualização dos mapas de ativação para entender como a CNN reconhece os dígitos.
  
     Exemplo de ativação de neurônios para reconhecimento do número 2 na primeira camada:
     
     ![image](https://github.com/user-attachments/assets/443fad2b-405e-4864-9778-53acdab94089)


## Como executar o projeto

1. Clone o repositório

   ``` git clone https://github.com/luizcaixeta/digit-recognizer.git ```

2. Execute o Jupyter Notebook:

   ``` jupyter notebook notebooks/digit-recognizer.ipynb ```

3. Siga a leitura do notebook.

Após o treinamento este modelo alcançou 97.54% de acurácia e 0.7% de perda, resultado que considero satisfatório dada a quantidade de dados disponíveis para treino.

