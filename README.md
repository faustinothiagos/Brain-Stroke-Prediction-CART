# Brain-Stroke-Prediction-CART

Este projeto consiste no uso de um banco de dados,  sobre aprevisão de acidentes vascular celebral. Aplicando uma técnica de machine learning o CART (lassification and regression trees).

<div align="center">
<img src="https://user-images.githubusercontent.com/97195240/184421651-273a6be5-3d47-4b05-abad-52c2449dea7f.jpg" width="400px" />
</div>

# Àrvore de classificação

<a id="section_beneficios"></a> 
### Benefícios da implementação de Árvores de Decisão:
- São fáceis de interpretar e podem ser representados graficamente.
- Podem capturar padrões não lineares.
- Podem lidar com dados numéricos e categóricos. Podem lidar com variáveis categóricas sem a necessidade de implementar uma codificação do tipo one hot encoding.
- Requer menos preparação de dados. Não é necessário normalizar o conjunto de dados.

<a id="section_desventajas"></a> 
### Desvantagens:
- As árvores não são robustas, pois são muito sensíveis a mudanças no conjunto de dados. Uma pequena alteração no conjunto de dados pode gerar uma árvore completamente diferente.
- Possuem uma tendência natural ao Overfitting.
- A precisão tende a diminuir para variáveis contínuas.
- Existem outros modelos que possuem maior precisão.
- As árvores de decisão geralmente são muito afetadas por conjuntos de dados que não são balanceados.
- O ótimo global não é garantido: como cada etapa busca maximizar o ganho de informação, esta metodologia não pode necessariamente garantir o resultado ótimo global.

<a id="section_desventajas"></a> 
## Marco teórico
Uma árvore de decisão se parece com a figura abaixo:

<div align="center">
<img src="https://user-images.githubusercontent.com/97195240/185018083-de217bc4-8573-4d6a-a22a-b08e5b1ac53f.jpeg" width="600px" />
</div>  
  
Uma árvore de decisão é uma estrutura semelhante a um fluxograma, por isso as árvores de decisão são fáceis de entender e interpretar. As árvores são compostas pelas seguintes partes:
- Cada **Nó de Decisão** representa uma característica (ou atributo),
- Cada **Ramo** representa uma regra de decisão.
- Cada **nó Folha** representa o resultado.
- O nó superior em uma árvore de decisão é conhecido como **nó raiz**.
- O nó do qual outros nós são desanexados é chamado de **nó pai** e os nós que são desanexados do nó pai são chamados de **nós filhos**
- Cada ramo que não é um nó folha pode ser considerado como uma **sub-árvore**.

- [Acessar a documentação do Scikit-learn](https://scikit-learn.org/stable/modules/tree.html#classification) 
- [Acesso rápido ao DataSet](https://github.com/faustinothiagos/CART_Classification_and_Regression_Trees/tree/main/DataSet) 
- [Acesso rápido ao Jupyter Notebook](https://github.com/faustinothiagos/CART_Classification_and_Regression_Trees/tree/main/Code)

### Objetivos deste projeto:

- Utilizando o conjunto de dados para pevenção de acidente vascular celebral. 

<div align="center">
<img src="https://user-images.githubusercontent.com/97195240/186544560-c24b50f3-4dcb-4556-aee0-cfb7d0618629.jpeg" width="400px" />
</div> 

- Selecionar os dados para modelar. 
- Treinar o modelo de teste de classificação nesses dados.
- Avaliar o desempenho do modelo e comparar vantagens e desvantagens.
- Determinar a importância dos recursos incluidos na previsão. Interpretar.
