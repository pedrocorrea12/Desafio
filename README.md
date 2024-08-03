# Desafio Python
Implemente um algoritmo de clusterização (como K-means) para segmentar os
clientes com base em seu comportamento de compra. Utilize métricas como
frequência de compra, valor médio de pedido e recência da última compra.
Visualize os clusters em um gráfico de dispersão 3D e forneça insights sobre as
características de cada grupo de clientes.

Primeiramente fiz o append e o join, e outros tratamentos de dados, diretamente pelo power query do excel e importei o arquivo pronto para o Colab.
Em seguida, fiz alguns cálculos básicos. Primeiro, determinei a frequência de compra de cada cliente, ou seja, quantas vezes cada um comprou. Também calculei o valor médio de cada pedido e a recência, que é o número de dias desde a última compra de cada cliente.
Depois, preparei os dados para a clusterização. Criei um DataFrame com essas informações e normalizei os dados para que ficassem na mesma escala. Usei o algoritmo K-means para dividir os clientes em três grupos, apenas para exemplificar como eles podem ser agrupados com base nas suas compras.
Finalmente, criei um gráfico 3D para visualizar esses grupos de clientes, mostrando como eles se distribuem conforme a frequência de compra, o valor médio do pedido e a recência.
