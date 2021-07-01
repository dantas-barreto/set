# Set

- ### Representa um conjunto de elementos (semelhante à álgebra)
  - Não admite repetições
  - Elementos não possuem posição
  - Acesso, inserção e remoção de elementos são rápidos
  - Oferece operações eficientes de conjunto: interseção, união e diferença.
  - Principais implementações:
    - **HashSet** - mais rápido (operações O(1) em tabela hash) e não ordenado
    - **TreeSet** - mais lento (operações O(log(n)) em árvore rubro-negra) e ordenado pelo `compareTo` do objeto (ou Comparator)
    - **LinkedHashSet** - velocidade intermediária e elementos na ordem em que são adicionados
