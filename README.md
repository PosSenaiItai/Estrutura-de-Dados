# Estrutura-de-Dados

# Árvores Binárias de Busca (ABB) 
São estruturas de dados de árvore binária onde todos os nós da subárvore esquerda possuem um valor menor ou igual ao valor do nó raiz e todos os nós da subárvore direita possuem um valor maior ou igual ao valor do nó raiz.
Essa propriedade garante que, para buscar um valor em uma ABB, basta começar na raiz e, comparando o valor procurado com o valor da raiz, seguir para a subárvore esquerda ou direita, conforme necessário. O algoritmo de busca em ABB é recursivo .
A complexidade da busca em ABB é de O(log n), onde n é o número de nós da árvore. Isso ocorre porque, no pior caso, a busca terá que percorrer toda a árvore até encontrar o valor procurado.
As ABBs são estruturas de dados muito eficientes para buscas, pois garantem que a busca sempre terá uma complexidade de O(log n). Além disso, as ABBs também podem ser usadas para outras operações, como inserção, remoção e ordenação.
# Exemplo de Árvore Binária de Busca

A figura a seguir mostra um exemplo de Árvore Binária de Busca com os valores 1, 2, 3, 4, 5, 6, 7, 8, 9:

             5
           /   \
         2      7
       /  \    /  \
     1     3  6    8
             \       \
              4        9
Nessa árvore, o valor 5 é o nó raiz. Os nós da subárvore esquerda possuem um valor menor ou igual a 5, enquanto os nós da subárvore direita possuem um valor maior ou igual a 5.

Para buscar o valor 3 nessa árvore, basta começar na raiz e comparar o valor 3 com o valor da raiz. Como 3 é menor que 5, seguimos para a subárvore esquerda. Na subárvore esquerda, encontramos o nó 3, que é o valor que estamos procurando.

# Aplicação prática das Árvores Binárias de Busca

As ABBs são usadas em uma variedade de aplicações, incluindo:

# Indexação de dados
# Geração de números aleatórios
# Árvores de expressão aritmética
# Árvores de decisão

# Indexação de dados

As ABBs são frequentemente usadas para indexar dados, como arquivos ou bancos de dados. Isso ocorre porque as ABBs permitem que as consultas sejam realizadas de forma rápida e eficiente.

Por exemplo, imagine que temos um arquivo com os nomes de todos os funcionários de uma empresa. Para encontrar o nome de um funcionário específico, podemos usar uma ABB para indexar o arquivo. A ABB nos permitirá encontrar o nome do funcionário em tempo O(log n), onde n é o número de funcionários.

# Geração de números aleatórios

As ABBs também podem ser usadas para gerar números aleatórios. Isso ocorre porque as ABBs podem ser usadas para gerar números pseudoaleatórios.

Um número pseudoaleatório é um número que parece ser aleatório, mas que é gerado por um algoritmo. Os números pseudoaleatórios são usados em uma variedade de aplicações, como jogos, criptografia e simulação.

# Árvores de expressão aritmética

As ABBs também podem ser usadas para representar árvores de expressão aritmética. Uma árvore de expressão aritmética é uma árvore que representa uma expressão aritmética.

Por exemplo, a expressão aritmética (2 + 3) * 4 pode ser representada pela seguinte árvore de expressão aritmética:

      *
    / \
   +   4
  / \
 2   3
As árvores de expressão aritmética são usadas para avaliar expressões aritméticas.

# Árvores de decisão

As ABBs também podem ser usadas para representar árvores de decisão. Uma árvore de decisão é uma árvore que representa uma sequência de decisões.

Por exemplo, uma árvore de decisão pode ser usada para decidir qual tratamento médico é mais adequado para um paciente.

As árvores de decisão são usadas em uma variedade de aplicações, como diagnóstico médico, análise financeira
