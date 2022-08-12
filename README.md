# Spark-MLLib-Sistema-Recomencadao (ALS)

O intuito deste codigo é mostrar como se aplicar o algoritmo para sistema de recomendação (ALS) através do PySpark, mostrar as bibliotecas, fazer análise exploratória, alguns jeitos de programar para poder fazer a limpeza e o pré-processamento dos dados.

Vai ser utilizado um dataset em que temos o id do usuario, o produto comprado e a nota que ele deu. O algoritmo vai se basear no metodo ALS que otimiza a loss function conseguindo fazer os scores para a afindade das recomendações, dai conseguir predizer qual a chance/nota do usuário comprar aquele item.

<strong> Descrição </strong>
<ul style="list-style-type:square">
  <li>Também chamado de filtros colaborativos.</li>
  <li>Analisa dados passados para compreender comportamentos de pessoas/entidades.</li>
  <li>A recomendação é feita por similaridade de comportamento.</li>
  <li>Recomendação baseada em usuários ou items.</li>
  <li>Algoritmos de Recomendação esperam receber os dados em um formato específico: [user_ID, item_ID, score].</li>
  <li>Score, também chamado rating, indica a preferência de um usuário sobre um item. Podem ser valores booleanos, ratings ou mesmo volume de vendas.</li>
</ul>
