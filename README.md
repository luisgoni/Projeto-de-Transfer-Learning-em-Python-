# Projeto Transfer Learning - Classificação Binária (Cats vs Dogs)

Este projeto utiliza Transfer Learning com o modelo MobileNetV2 para classificar imagens de gatos e cachorros usando o dataset do TensorFlow Datasets.

## Principais etapas

- **Carregamento do dataset**: Utiliza o `cats_vs_dogs` do TensorFlow Datasets, dividido em treino, validação e teste.
- **Pré-processamento**: Redimensiona as imagens para 224x224 pixels e normaliza para o intervalo esperado pelo MobileNetV2.
- **Modelo**: Utiliza MobileNetV2 pré-treinado, com uma camada final `Dense(1, activation='sigmoid')` para classificação binária.
- **Treinamento**: Usa `binary_crossentropy` como função de perda e EarlyStopping para evitar overfitting.
- **Ajuste fino**: Descongela parte das camadas do modelo base para melhorar a performance.
- **Avaliação**: Mostra acurácia no conjunto de teste e gráficos de perda/acurácia.

## Como executar

1. Instale as dependências:
    ```bash
    pip install tensorflow tensorflow-datasets matplotlib
    ```
2. Execute o notebook `Transfer_Learning_Binary.ipynb` no Google Colab ou Jupyter Notebook.

## Observações

- O projeto pode ser adaptado para outros datasets binários.
- Para usar outras imagens, basta ajustar o carregamento e o pré-processamento.

---

**Autor:** Luis Gustavo  
**Base:** [Kaggle Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)