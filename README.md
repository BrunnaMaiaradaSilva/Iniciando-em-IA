#Como algoritmos aprendem?

Cães e gatos são animais peludos com quatro patas e muitas outras características em comum. Por que, então, é tão fácil distinguir um gato de um cachorro?

Quando somos crianças, aprendemos quais animais são cães e quais são gatos com os ensinamentos de outras pessoas. Muito rapidamente, paramos de precisar de novos exemplos. Nosso aprendizado é poderoso o suficiente para classificar um novo animal como cachorro ou gato, mesmo quando não se parece particularmente com o que já vimos antes. Acontece que os computadores podem aprender da mesma forma.

Um algoritmo de aprendizado supervisionado tenta modelar uma função para relacionar entradas e saídas, você dá entradas como amigável e planeja matar a humanidade e produz saídas como: cachorro e gato, respectivamente. O algoritmo usa exemplos conhecidos para aprender esse relacionamento. Ao criar um modelo de aprendizado supervisionado para distinguir se a imagem é de um cachorro ou gato, quais devem ser as entradas para os exemplos? Cor do pelo? Late? Mia? Ou dados numéricos representando imagens de cães e gatos?

Dados numéricos representando imagens de cães e gatos é a resposta correta. Se você deseja identificar se um animal é um cachorro ou um gato, é natural que suas informações sejam imagens de cães e gatos. Normalmente, esses dados são representados por uma matriz de valores numéricos que correspondem a cada pixel em uma imagem. Além disso, esses dados serão os mais úteis para o treinamento do modelo, pois permitirão que um computador aprenda da mesma forma que os seres humanos, “vendo” as imagens e encontrando padrões entre elas. Obviamente, um computador precisará de mais exemplos do que um humano para poder distinguir com sucesso entre a maioria dos cães e gatos.

Suponha que você tenha acesso a 100.000 imagens de cães e gatos que você pode usar para criar um modelo de aprendizado supervisionado que distinga entre cães e gatos. Depois de usar imagens como exemplos para treinar (ou ensinar) o modelo, convém usar imagens para testar o modelo; isto é, para determinar se o modelo é realmente bem-sucedido em identificar se a imagem é de um cachorro ou gato. Qual seria uma maneira razoável de selecionar suas imagens para treinamento e teste?

_Como testar um modelo?_

Dividindo as imagens aleatoriamente em dois conjuntos: um para treinamento e outro para teste O objetivo final do aprendizado supervisionado é encontrar uma função que modele o relacionamento entre as entradas e saídas, o que significa que ele deve ser capaz de prever uma saída, dada uma nova entrada que ela nunca viu antes. Isso é conhecido como generalização. Portanto, precisamos avaliar quão bem o modelo e o algoritmo de aprendizado generalizam os dados observados para os dados não observados. Uma maneira simples de fazer isso é dividir os dados de entrada em dois conjuntos, um conjunto para treinar o modelo e outro para avaliar quão bem ele generaliza. O primeiro conjunto é conhecido como dados de treinamento, pois é o que o modelo usa para treinar. O segundo conjunto é conhecido como dados de teste, pois é usado para avaliar a capacidade de generalização do modelo e do algoritmo de aprendizado. Como realmente dividir esses dados (ou seja, qual proporção de dados a ser salva para teste) depende do problema em questão e dos dados disponíveis. O que veremos no próximo commit!
