# Homer-vs-Bart-CNN

Este projeto implementa uma Rede Neural Convolucional (CNN) para classificar imagens dos personagens Homer e Bart Simpson. O modelo foi treinado usando PyTorch e um dataset personalizado.

## Descrição do Projeto

Este projeto demonstra como construir e treinar uma CNN para classificação de imagens usando PyTorch. O modelo utiliza uma arquitetura ResNet18 pré-treinada e foi ajustado para classificar imagens dos personagens Homer e Bart Simpson. O código inclui funcionalidades para carregamento do dataset, treinamento do modelo, avaliação do desempenho e visualização de predições.

## Dataset

O dataset utilizado neste projeto consiste em imagens dos personagens Homer e Bart Simpson, organizadas em pastas separadas para treino e teste. A estrutura do dataset é a seguinte:


dataset_personagens/

├── training_set/
│ ├── homer/
│ │ ├── homer_imagem1.jpg
│ │ ├── homer_imagem2.jpg
│ │ └── ...
│ └── bart/
│ ├── bart_imagem1.jpg
│ ├── bart_imagem2.jpg
│ └── ...
└── test_set/

├── homer/
│ ├── homer_imagem1.jpg
│ ├── homer_imagem2.jpg
│ │ └── ...

└── bart/
├── bart_imagem1.jpg
├── bart_imagem2.jpg
└── ...


## Como Executar o Projeto

```
1. **Clone o repositório:**

git clone https://github.com/dede0702/Homer-vs-Bart-CNN.git

Instale as dependências:

pip install -r requirements.txt


Baixe o dataset: (https://github.com/dede0702/Homer-vs-Bart-CNN/blob/6142766d5348364639aae58a89963679c798d733/dataset_personagens.zip)

Resultados

O modelo alcançou uma acurácia de [insira a acurácia aqui]% no conjunto de teste. (Lembre-se de atualizar este valor após o treinamento).

Visualização

O código inclui uma função para visualizar as predições do modelo em algumas imagens do conjunto de teste. As imagens e as predições serão exibidas em uma janela matplotlib.
```

Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com suas melhorias.

Licença

MIT License

Copyright (c) 2024 André Rovai Jr

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Contato

André Rovai Jr - andrerovaijr722@gmail.com


