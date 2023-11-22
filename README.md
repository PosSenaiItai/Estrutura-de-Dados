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
