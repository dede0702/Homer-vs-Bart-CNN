# Classificação de Imagens: Homer vs Bart usando Redes Neurais Convolucionais (CNN)

Este projeto utiliza redes neurais convolucionais (CNN) para a classificação de imagens dos personagens Homer e Bart do desenho animado *Os Simpsons*. O objetivo é treinar um modelo capaz de identificar corretamente os personagens em imagens e marcar o local onde eles são encontrados com um retângulo ao redor.

## Pré-requisitos

Certifique-se de que as seguintes bibliotecas estão instaladas. Para facilitar o processo, foi gerado o arquivo `requirements.txt`, que contém todas as dependências necessárias para rodar o projeto.

### Instalação das dependências

1. Clone o repositório do projeto para o seu ambiente local:

```bash
git clone <URL_do_Repositorio>
```

2. Navegue até o diretório do projeto:

```bash
cd Homer_vs_Bart_CNN
```

3. Utilize o `pip` para instalar as dependências:

```bash
pip install -r requirements.txt
```

## Estrutura do Projeto

- `dataset/`: Pasta contendo as imagens de treino e teste dos personagens Homer e Bart.
- `Homer_vs_Bart_CNN.ipynb`: Arquivo Jupyter Notebook com o código principal para o treinamento e avaliação do modelo.
- `model/`: Diretório onde o modelo treinado é salvo.
- `requirements.txt`: Arquivo que lista todas as bibliotecas e dependências necessárias para rodar o projeto.

## Funcionamento do Código

O modelo é baseado em uma rede neural convolucional (CNN) construída com o Keras e TensorFlow. O código segue o seguinte fluxo:

1. Pré-processamento dos Dados: As imagens são carregadas e redimensionadas para o formato esperado pela CNN.
2. Divisão do Dataset: Utiliza-se a função `train_test_split` do scikit-learn para dividir os dados em conjuntos de treino e teste.
3. Criação da CNN: O modelo CNN é construído com camadas convolucionais e pooling, seguido de camadas densas para a classificação.
4. Treinamento: O modelo é treinado com os dados de treino, utilizando augmentação de imagens para melhorar a generalização.
5. Avaliação: O modelo é avaliado no conjunto de teste para medir sua precisão.
6. Predição e Visualização: Após o treinamento, o modelo faz previsões sobre novas imagens e exibe a imagem do personagem identificado, destacando-o com um retângulo ao redor.

## Erro Comum: Importação

Durante a execução, você pode encontrar erros de importação relacionados ao `reportMissingImports`. Para corrigir esse erro, certifique-se de que todas as bibliotecas estão instaladas corretamente. Recomenda-se o uso de um ambiente virtual (virtualenv) para organizar as dependências.

## Como Executar o Projeto

1. Clone este repositório para o seu ambiente local:

```bash
git clone <URL_do_Repositorio>
```

2. Navegue até o diretório do projeto:

```bash
cd Homer_vs_Bart_CNN
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Abra o arquivo `Homer_vs_Bart_CNN.ipynb` no Jupyter Notebook:

```bash
jupyter notebook Homer_vs_Bart_CNN.ipynb
```

5. Execute todas as células para treinar o modelo e visualizar os resultados.

## Melhorias Futuras

- Aprimorar o Desempenho do Modelo: Testar arquiteturas de CNN mais avançadas, como VGG16, ResNet ou Inception, para melhorar a precisão e o desempenho da classificação.
- Aprimoramento do Dataset: Incluir mais imagens variadas dos personagens, com diferentes ângulos e expressões, para melhorar a robustez do modelo.
- Implementar Regularização: Adicionar técnicas de regularização como dropout, L2 regularization ou batch normalization para evitar overfitting.
- Avaliação de Métricas Alternativas: Implementar outras métricas além da acurácia, como F1-score, precisão e recall, para uma análise mais completa do desempenho do modelo.
- Deploy do Modelo: Criar uma API (usando Flask ou FastAPI) para que o modelo possa ser utilizado por outras aplicações.
- Documentação Detalhada do Código: Adicionar mais comentários e explicações no código para facilitar a compreensão e manutenção por outros desenvolvedores.
- Interface Gráfica Simples (GUI): Desenvolver uma interface gráfica simples para que os usuários possam carregar imagens e visualizar as previsões sem a necessidade de acessar diretamente o código.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Para fazer isso, siga os passos:

1. Fork o repositório.
2. Crie uma nova branch: `git checkout -b minha-nova-feature`.
3. Faça commit das suas alterações: `git commit -m 'Adicionei uma nova feature'`.
4. Envie para o branch original: `git push origin minha-nova-feature`.
5. Crie um pull request.

---

Com essas informações, o README está mais completo e inclui os detalhes sobre o uso do arquivo `requirements.txt`. Se precisar de mais algum ajuste ou adicionar outra seção, estou à disposição!
