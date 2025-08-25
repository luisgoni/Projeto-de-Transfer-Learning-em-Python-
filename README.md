# Projeto Transfer Learning - Cats vs Dogs 🐱🐶

Este projeto utiliza Transfer Learning com a arquitetura MobileNetV2 para classificar imagens de gatos e cachorros usando o dataset [Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs) do TensorFlow Datasets.

## Estrutura do Projeto

- **Pré-processamento:** Redimensionamento, aumento de dados e normalização das imagens.
- **Modelo:** MobileNetV2 pré-treinado, com ajuste fino (fine-tuning) nas últimas camadas.
- **Treinamento:** EarlyStopping para evitar overfitting.
- **Avaliação:** Matriz de confusão, relatório de classificação e visualização de resultados.
- **Exportação:** Salva o modelo em formato Keras (`.h5`).

## Como Executar

1. Instale as dependências:
    ```sh
    pip install tensorflow tensorflow-datasets scikit-learn matplotlib pillow
    ```

2. Execute o notebook [`Transfer_Learning_test_1.ipynb`](c:\Users\Luis Gustavo\Downloads\Transfer_Learning_test_1.ipynb) passo a passo.

3. O modelo será treinado, avaliado e salvo como `cats_vs_dogs_model.h5`.

## Resultados

- Acurácia de teste: ~99%
- Matriz de confusão e relatório de classificação disponíveis no notebook.
- Visualização das previsões do modelo em imagens do conjunto de teste.


## Referências

- [Documentação TensorFlow](https://www.tensorflow.org/)
- [Dataset Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs)

---

**Autor:** **Luis Gustavo (Goni)** 
**Contato:** <a href="https://wwwlinkedin.com/in/luisamaral2506/">
        <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin" alt="LinkedIn">

